+++
title = "Deploy Spring boot application to AWS Cloud"
date = 2021
weight = 1
chapter = false
+++

# Deploy Spring boot application to AWS Cloud

#### Overview

In this lab, we will deploy a Spring Boot application to AWS Cloud using EC2 instances to ensure the application's scalability based on user demand. This deployment will enable us to efficiently handle varying traffic levels from users accessing the application

After completing the workshop, the architecture is as follows:
![Diagram](../../../images/spring-boot-demo-aws.jpg?width=45pc)


#### Content:
1. [Introduction](1-prerequisite)
2. [Create Security Group and Key Pair](2-SW-and-Key)
3. [Create EC2 instance](3-EC2-intance)
4. [Connect EC2 via ssh](4-connection)
5. [Prepare and build the Springboot application](5-sourcecode) 
6. [Deploy the application to the EC2 instance](6-deploy)
7. [Clean up resources](7-cleanup)