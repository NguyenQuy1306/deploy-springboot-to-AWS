+++
title = "Prepare and build the Springboot application"
date = 2020
weight = 5
chapter = false
pre = "<b>5. </b>"
+++

In this part, we will create your Springboot application and push it to docker hub.

Follow these steps:

1. Prepare Your Spring Boot Application
  * Ensure your Spring Boot application is working correctly
  * Add a Dockerfile in the root of your project.
![Diagram](../../../images/5/1.png?width=40pc)

2.  Build and Push Docker Image to Docker Hub
  * Build Docker Image by running the following command:
  ```bash
  docker build -t your-dockerhub-username/your-app-name .
  ``` 

* Login to Docker Hub:
  ```bash
  docker login
  ```  

* Push Docker Image to Docker Hub:
  ```bash
  docker push your-dockerhub-username/your-app-name
  ```  
* Finally, go to docker hub and check the image have been created:

![Diagram](../../../images/5/2.png?width=40pc)