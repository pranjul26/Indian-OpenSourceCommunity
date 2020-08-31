# Indian-OpenSourceCommunity
# 1. Launching one windows instance with IIS server.

  •	Launch one T2 micro type windows server instance on AWS.
  •	Configure an IIS server with default web page.

# 2. EC2- Classic Load Balancer

• Create 2 Ec2 windows free tier instances.
• Configure IIS server on both. Be sure you are configuring them on two different availability zones for achieving high availability.
• Configuring a classic load balancer between those two instances with HTTP service port.
