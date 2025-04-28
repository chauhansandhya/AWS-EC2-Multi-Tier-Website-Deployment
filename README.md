# AWS-EC2-Multi-Tier-Website-Deployment

## 1. Multi-Tier Website Deployment Using AWS EC2 & RDS

### Overview
Migrated a PHP-MySQL web application to AWS using a scalable and highly available architecture. Implemented Auto Scaling and managed the database layer with Amazon RDS.

### Features
- EC2 Instances to host PHP website.
- Auto Scaling Group with minimum of 2 instances.
- Amazon RDS for managed MySQL database (`intel`).
- Security Groups to control access between EC2 and RDS.
- Traffic handling optimization with Auto Scaling policies.

### Architecture
- Frontend: PHP Website hosted on EC2
- Backend: MySQL Database on RDS
- Networking: Security Groups to allow safe communication

### Technologies
AWS EC2, AWS RDS, Auto Scaling, MySQL, PHP, VPC, Security Groups

---

## 2. Secure Healthcare Messaging Using Amazon SNS

### Overview
Designed a secure notification system for delivering sensitive healthcare reports via Amazon SNS within a private VPC, ensuring encrypted and private message distribution.

### Features
- AWS CloudFormation template to create isolated VPC.
- Amazon SNS for publishing secure patient reports.
- EC2 instance hosting message publishing services.
- Encrypted, private message delivery to ensure data protection.
- Mobile push notifications integration for patients.

### Architecture
- Private VPC with necessary subnets and security controls
- SNS Topic for private report delivery
- EC2 for internal operations

### Technologies
AWS SNS, AWS EC2, AWS VPC, AWS CloudFormation, IAM, Push Notifications

## Skills Highlighted

- Cloud Infrastructure Setup (AWS EC2, RDS, VPC)
- Infrastructure as Code (AWS CloudFormation)
- Auto Scaling and High Availability Configuration
- Security Best Practices for Cloud Environments
- Messaging Services with Amazon SNS
- Basic DevOps Practices (Automation, Scalability, Monitoring Potential)

