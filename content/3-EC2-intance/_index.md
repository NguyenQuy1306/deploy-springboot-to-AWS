+++
title = "Create EC2 instance"
date = 2021
weight = 3
chapter = false
pre = "<b>3. </b>"
+++

In this part, we will create EC2 instance in aws. 

Follow these steps:

1. Access the AWS Management Console
  * Search for EC2
  * Select EC2
![Diagram](../../../images/2/1.png?width=40pc)

2. On the left of page EC2
  * Click **Intances**
  * Then, click **Launch instance** to create a new instance
![Diagram](../../../images/3/5.png?width=40pc)

3. At page Create EC2 instance
  * Fill in your  **Instance name**
![Diagram](../../../images/3/6.png?width=40pc)  
  * Choose application and OS images is  **Amazon linux**
![Diagram](../../../images/3/7.png?width=40pc)  
  * In Instance type, choose the instance type as follows: 
![Diagram](../../../images/3/8.png?width=40pc)  
  * In key pair, choose the key pair that you have created before 
![Diagram](../../../images/3/9.png?width=40pc)  
  * In network settings, choose VPC **default**
  * Click **Select existing security group** because you have created a security group for this instance in previous section.
![Diagram](../../../images/3/10.png?width=40pc)  
* In this project, we just need 1 instance. So, don't adjust the number of instance. 
* Finally, click **launch instance** to create instance. 
![Diagram](../../../images/3/11.png?width=40pc) 
4. Result 
![Diagram](../../../images/3/12.png?width=40pc)  