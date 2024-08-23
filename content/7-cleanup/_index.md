+++
title = "Clean up resources"
date = 2021-06-08T18:57:03+07:00
weight = 7
chapter = false
pre = "<b>7. </b>"
+++

In this part, we will clean up the resouces after deploy succesfully:
1. **Access the AWS Management Console**
  * Search for EC2
  * Select EC2
![Diagram](../../../images/2/1.png?width=40pc)
2. **Delete EC2 instance**:
  * Access to **intances** 
  * Click choose instance
  * Click **instance state**
  * Then choose **terminate (delete) instance**
![Diagram](../../../images/7/1.png?width=40pc)
  * Continue click  **Terminate (delete)**
![Diagram](../../../images/7/2.png?width=40pc)

3. **Result**
![Diagram](../../../images/7/3.png?width=40pc)

4. **Xóa Security Group**
    - Truy cập **EC2 Management Console** 
    - Trên thanh điều hướng bên trái, chọn Security Groups
    - Chọn tất cả Security Groups liên quan tới bài lab.
    - Click Actions.
    - Click Delete security groups
    - Click Delete