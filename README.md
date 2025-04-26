3-Tier Web Application Deployment on AWS
Overview
This project demonstrates the design, deployment, and management of a 3-tier web application architecture on Amazon Web Services (AWS). The architecture consists of the following layers:

Presentation Layer (Web Tier): Responsible for handling user interactions.
Application Layer (App Tier): Processes business logic and application functionality.
Database Layer (DB Tier): Manages secure and scalable data storage.
The primary focus is on building a scalable, secure, and highly available architecture using AWS services.

Architecture
The 3-tier architecture is structured as follows:

Web Tier:
EC2 instances running a web server (e.g., Apache, Nginx) behind an Elastic Load Balancer (ALB) for distributing traffic.
Application Tier:
EC2 instances or managed services like AWS Elastic Beanstalk that execute business logic.
Database Tier:
Amazon RDS (e.g., MySQL, PostgreSQL) deployed in a private subnet.
AWS Services Used
VPC (Virtual Private Cloud): Custom networking for the application.
EC2 (Elastic Compute Cloud): Virtual servers for web and application tiers.
ELB (Elastic Load Balancer): Distributes traffic across EC2 instances.
Auto Scaling Groups: Ensures scalability and high availability.
Amazon RDS (Relational Database Service): Secure and scalable database backend.
IAM (Identity and Access Management): Manages access and permissions.
Route 53 (Optional): Domain name management.
CloudWatch: Monitoring and logging for performance and reliability.
S3 (Optional): Static file storage.
Project Goals
Understand and implement a standard 3-tier architecture.
Deploy a scalable and fault-tolerant web application on AWS.
Learn security best practices (subnets, security groups, IAM roles).
Monitor and optimize application performance.
Prerequisites
An active AWS account.
Basic knowledge of AWS services.
Familiarity with Linux, networking, and web servers.
Steps to Deploy
Create the VPC:
Set up public and private subnets, route tables, and internet gateways.
Deploy the Web Tier:
Launch EC2 instances and configure the Elastic Load Balancer.
Configure the Application Tier:
Launch EC2 instances or use AWS Elastic Beanstalk.
Set up the Database Tier:
Deploy Amazon RDS in a private subnet.
Configure Security:
Set up security groups, IAM roles, and policies.
Optional Enhancements:
Use Route 53 for custom domain names.
Store static files in S3.
Monitoring and Logging
Use CloudWatch to monitor metrics such as CPU utilization, disk I/O, and network traffic.
Set up CloudWatch alarms for proactive response to performance issues.
Tools and Technologies
AWS Management Console and CLI
Web server (e.g., Apache, Nginx)
Database (e.g., MySQL, PostgreSQL)

Link : http://webtierexternallb-1308437139.ap-south-1.elb.amazonaws.com/#/
