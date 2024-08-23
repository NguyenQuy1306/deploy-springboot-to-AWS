+++
title = "Deploy the application to the EC2 instance"
date = 2020
weight = 6
chapter = false
pre = "<b>6. </b>"
+++

In this part, we will deplot Springboot application into EC2 server.

Follow these steps:

1. If you have connected to EC2 by ssh then go to step 2 else go back section 4.
   
   [Section 4](4-connection)
2. Open powershell in your computer:
  * Install Docker by running the following command:
  ```bash
  sudo yum install -y docker
  ``` 
![Diagram](../../../images/6/1.png?width=40pc)
3. Start docker:
  ```bash
  sudo service docker start
  ```  
![Diagram](../../../images/6/2.png?width=40pc)
* Then, check container is running:
  ```bash
  sudo docker ps
  ```  
![Diagram](../../../images/6/3.png?width=40pc)
 * Now, you can see that it has no container is running.
4. Run docker image:
  ```bash
  sudo docker run -d -p 80:8080 yourdockerimage:tag
  ```  
![Diagram](../../../images/6/4.png?width=40pc)
5. Check container is running again:
  ```bash
    sudo docker ps
  ```  
![Diagram](../../../images/6/5.png?width=40pc)
  * Now, you can see that it has a conternain is running!
6. Open the server by IP address of EC2:
  * Back to AWS
  * Open instance detail
  * Copy the puclic IPv4 of instance
   ![Diagram](../../../images/6/6.png?width=40pc)
  * New tab, and paste the IPv4
  * Then, you can see the server is running successfully in AWS.
   ![Diagram](../../../images/6/7.png?width=40pc)