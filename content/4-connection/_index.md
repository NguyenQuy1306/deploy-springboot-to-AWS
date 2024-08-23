+++
title = "Connect EC2 via ssh"
date = 2020
weight = 4
chapter = false
pre = "<b>4. </b>"
+++

In this part, we will create a connection to EC2 instance by ssh. 

Follow these steps:

1. Access the AWS Management Console
  * Search for EC2
  * Select EC2
![Diagram](../../../images/2/1.png?width=40pc)

2. On the left of page EC2
  * Click **Intances**
  * Then, click your instance to view detail 
![Diagram](../../../images/3/1.png?width=40pc)

1. At page detail 
  * You can see public IPv4 address of the instance
  * Copy this address.
![Diagram](../../../images/4/1.png?width=40pc)  
  * Next, open powershell in your computer
  * Then, type this "*ssh -i C:\Users\cnyegun\Downloads\spring-boot-demo.pem ec2-user@18.140.57.186*"
  * **Note**: You must adjust the ip adress on the right of  the symbol @ by your ip address of your instance in the command above.
![Diagram](../../../images/4/2.png?width=40pc)  
  * In the screen will ask you to accept to creat connect.
  * Type **Yes**
![Diagram](../../../images/4/3.png?width=40pc)  

2. Result 
![Diagram](../../../images/4/4.png?width=40pc)  