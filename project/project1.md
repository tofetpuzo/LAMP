## LAMP STACK IMPLEMENTATION 
---

What is LAMP?
LAMP stands for L : Linux, A: Apache, M: mySQL, P: PHP.

These aforementiomed components or software allow to build and deliver high performance web applications.                           How it works?
The LAMP stack shows how each element depends on each. Let us take an example, suppose a user sends a request to order an item from an-ecommerce store. 

The process starts off when the Apache web server recieves the requests from the web pages from a typical use's browser. This request is so for a PHP file, The Apache server then passes the information to PHP, which then loads the file and executes the code contained the file. 

Where does the mySQL come in; this is the database which provides the user all the necessary information about the items they intend to purchase.                               

Installation
---
The recommended way to implement LAMP, is first to create an AWS account. Using this link:
 [AWS_ACCOUNT](https://signin.aws.amazon.com/)

 The create page looks like this.

 ![aws](./images/aws.png) 

 After signing up, I logged into the aws account as a root user, this allowed me to have access into the aws management console, where I searched for EC2: Elastic cloud compute from the search bar, shown below.
 ![ec2](./images/ec2.png).

Create an EC2 instance of t2.micro, requires selecting a software such as Ubuntu 20.04LTS. 

This allows for easily communication between the instance and my local machine.  
After setting up ec2 instance, the dashboard was similar to the figure below:
 ![instance](./images/instance.png).

 The next step before installing LAMP is to ensure my local machine and remote server communicates, I had to download the keypair usually attached to the instance of ec2, This allows for easy communication between my local machine and the remote server. 

### APACHE INSTALLATION
To install apache, the ubuntu packages must be up to date, to ensure this, this code was wr

 


 
After signing into the link.
Create an instance of the EC2 



check APACHE status

`sudo `







