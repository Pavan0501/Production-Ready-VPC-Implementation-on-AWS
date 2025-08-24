# Production-Ready-VPC-Implementation-on-AWS
Implemented a production-ready AWS VPC with multi-AZ subnets, NAT/Internet gateways, and secure routing.

This project demonstrates the deployment of a secure, scalable, and highly available AWS architecture using core AWS services such as VPC, EC2, Application Load Balancer (ALB), and Auto Scaling Groups (ASG).

Features:

•	Custom VPC with public and private subnets across multiple Availability Zones

•	Application Load Balancer (ALB) to route traffic to EC2 instances

•	Auto Scaling Group (ASG) for automatic instance scaling based on traffic

•	Internet Gateway & NAT Gateway setup for internet access management

•	Route tables configured to control traffic flow within the VPC

•	Bastion Host configured in a public subnet to securely access private EC2 instances via SSH

•	Designed for high availability, fault tolerance, and cost optimization

Technologies Used:

•	AWS EC2
•	AWS VPC (Subnets, Route Tables)
•	Application Load Balancer (ALB)
•	Auto Scaling Group
•	Internet Gateway & NAT Gateway
•	Security Groups
•	Bastion Host (Jump Box)
•	IAM (for secure access and permissions)
