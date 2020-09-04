# Indian-OpenSourceCommunity
# 1. Launching one windows instance with IIS server.

  •	Launch one T2 micro type windows server instance on AWS.
  •	Configure an IIS server with default web page.

# 2. EC2- Classic Load Balancer

• Create 2 Ec2 windows free tier instances.
• Configure IIS server on both. Be sure you are configuring them on two different availability zones for achieving high availability.
• Configuring a classic load balancer between those two instances with HTTP service port.

# 3. 2-Tier Application - Wordpress and MySQL

•	Launch 1 EC2 Linux instance and configure MySQL/Mariadb server on it (use your choice for password and user names). 
•	Launch 1 EC2 Linux instance and configure Wordpress Application server on it. 
•	Use previously configured MySQL or Mariadb database server for connection with private IP address of instances.

# 4. AWS CLI

Access your AWS account from linux terminal or windows command prompt / power shell and perform following task. Launch one instance with one free tier AMI on a free tier instance type and take its remote access (ssh/remote access).

# 5. Access different components of AWS using AWSCLI

Create a 3G EBS volume and attach it to one running instance and create a 1GB partition on that and mount it on one directory no need to make /etc/fstab entry. Remember all this thing using AWS CLI and terminal only.

# 6. IIS server on Windows server instance on Azure

Launch one free flavor/machine type with windows server (instance) on GCP/Azure. Configure an IIS server with your Default web page once, then also try to change the Index.html page. 
