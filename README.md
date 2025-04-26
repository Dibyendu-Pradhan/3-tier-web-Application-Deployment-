Overview:
This project demonstrates how to design, deploy, and manage a 3-tier web application architecture on Amazon Web Services (AWS).
It includes the Presentation Layer (Web Tier), Application Layer (App Tier), and Database Layer (DB Tier), all built with scalability, security, and high availability in mind.

Architecture:
The 3-tier architecture is structured as follows:

Web Tier: EC2 instances behind an Elastic Load Balancer (ALB), running a web server (e.g., Apache, Nginx).

Application Tier: EC2 instances (or managed services like AWS Elastic Beanstalk) that process the business logic.

Database Tier: Amazon RDS (e.g., MySQL, PostgreSQL) deployed in a private subnet for secure data storage.

AWS services used:

VPC (Virtual Private Cloud)

EC2 (Elastic Compute Cloud)

ELB (Elastic Load Balancer)

Auto Scaling Groups

Amazon RDS

IAM (Identity and Access Management)

Route 53 (optional for domain name management)

CloudWatch (for monitoring and logging)

S3 (for static file storage, optional)

Project Goals
Understand and implement a standard 3-tier architecture.

Deploy a scalable and fault-tolerant web application on AWS.

Learn best practices for security (subnets, security groups, IAM roles).

Monitor the application for performance and reliability.

Prerequisites
AWS Account

Basic knowledge of AWS Services

Familiarity with Linux, networking, and web servers
