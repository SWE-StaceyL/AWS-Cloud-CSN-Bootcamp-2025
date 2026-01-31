<img width="801" height="720" alt="email verification received" src="https://github.com/user-attachments/assets/df795a56-df86-47a0-a2a2-77e35acbde2c" /><img width="1900" height="633" alt="Welcome to Nginx" src="https://github.com/user-attachments/assets/4573d197-d11f-4977-aa71-098af62dd98d" />
Aws Cloud Csn Bootcamp – 2025

### Overview

This repository documents my hands-on learning journey through the AWS Cloud CSN Bootcamp (2025). The bootcamp was structured around weekly practical tasks (Week 1–10), each designed to build real-world AWS cloud skills through implementation, configuration, and troubleshooting directly in the AWS Management Console.

All tasks were completed individually on AWS, with evidence captured and organised by week.

### Week 1 – AWS Account Setup & Console Navigation

What I learned: AWS account setup and initial configuration Navigating the AWS Management Console Understanding core AWS services and regions.

How I accomplished it: Logged into the AWS Management Console. Explored the dashboard and service categories Verified account settings and console access

AWS Account
<img width="1764" height="949" alt="AWS Account" src="https://github.com/user-attachments/assets/04f0bf1c-a80e-4570-97cb-97db96804851" />
AWS Management Console
<img width="1858" height="950" alt="AWS Account  SM8" src="https://github.com/user-attachments/assets/e4d309e5-e858-4fb3-841e-f987d58d4199" />

### Week 2 – Identity & Access Management (IAM)

What I learned: AWS IAM fundamentals and Creating users and permission sets by Applying the principle of least privilege

How I accomplished it: Created a new IAM user then Assigned predefined job-function permission sets and Verified access using the AWS IAM Identity Center

Created New User
<img width="1873" height="866" alt="Created New User Stacey Munnik" src="https://github.com/user-attachments/assets/06e245f9-a947-4b68-b279-5ab3dd50d60d" />

Central Management Center
<img width="1857" height="915" alt="Central Management Center" src="https://github.com/user-attachments/assets/72eefc40-07e3-42e5-a98a-5b2ea186f771" />

Job Function & Description
<img width="1885" height="755" alt="Predefined Security Audit Job Function" src="https://github.com/user-attachments/assets/bc377279-1ab2-4764-8361-814674927c10" />

Permission Sets for New User
<img width="1901" height="733" alt="Permission sets for New User" src="https://github.com/user-attachments/assets/24cfb08f-e189-43af-ad05-e9ca00ebb407" />

Week 3 – Amazon EC2 (Compute)

What I learned: Launching and managing EC2 instances and Understanding instance states and public IPs, Remote access to cloud servers

How I accomplished it:I Launched an EC2 instance, Verified instance status and networking and Connected to the instance using remote desktop/SSH

EC2 Instance
<img width="1865" height="943" alt="EC2 Week 3 Task" src="https://github.com/user-attachments/assets/363788ac-cd3a-4723-b120-52d959a755d9" />

Running EC2 Instance
<img width="1901" height="799" alt="EC2" src="https://github.com/user-attachments/assets/0c02de3b-5ed2-420e-9762-d5f201a5f4bc" />

Launched Windows Server
<img width="907" height="665" alt="Screenshot 2025-06-21 221848" src="https://github.com/user-attachments/assets/02f5f996-4397-49e1-b1f6-4c986b344853" />

### Week 4 – Networking with Amazon VPC

What I learned: Virtual Private Cloud (VPC) architecture, Public and private subnet and VPC peering and route tables

How I accomplished it:I Created two VPCs (VPC-A and VPC-B) then Configured subnets, internet gateways, and route tables and 

Established VPC peering and verified connectivity.

Peering Connection
<img width="948" height="905" alt="peering connection 1" src="https://github.com/user-attachments/assets/223347ee-8797-4cab-bdd1-673d4fd12781" />

Created a Peering Connection VPC-A  to VPC-B
<img width="956" height="955" alt="Creating Peering Connection VPC-A to VPC-B" src="https://github.com/user-attachments/assets/273d6a53-ab68-4382-ad1f-41922785bf7c" />

<img width="948" height="950" alt="peering connection VPC-A to VPC-B Routes" src="https://github.com/user-attachments/assets/d6167888-8fc8-45d4-ab70-c5aefdc287eb" />

Internet Gateway
<img width="948" height="947" alt="VPC-A-IGW" src="https://github.com/user-attachments/assets/e5fdd053-e706-483b-99f1-4f17bdda0492" />

Public Subnets 
<img width="945" height="949" alt="VPC-A-Public-Private-Subnests" src="https://github.com/user-attachments/assets/b58a6b24-589e-4563-abd7-21a64cd8262c" />

### Week 5 – Containers with Amazon ECS (Grafana)

What I learned: Container orchestration using Amazon ECS, including Task definitions and clusters and Security groups and container networking.

How I accomplished it: I Created an ECS cluster then Deployed Grafana using task definitions and Configured security groups to expose port 3000. Finally, Verified Grafana service availability

Container Configuration
<img width="1574" height="772" alt="Container Detail Setup" src="https://github.com/user-attachments/assets/9309f18d-01db-4052-a743-de5ee450b8fe" />

<img width="1593" height="803" alt="csn-grafana-demo" src="https://github.com/user-attachments/assets/7c4be7ad-c0de-4e20-bd1a-70da7ff166fd" />

Grafana Task Definition
<img width="1601" height="834" alt="Grafana Task Definition" src="https://github.com/user-attachments/assets/3dd49bf0-55d5-48ae-ab9c-7c193e68c61b" />

Grafana Services
<img width="1593" height="620" alt="Grafana Services" src="https://github.com/user-attachments/assets/193d9d94-2f38-422e-9095-911f31618558" />

Task Running
<img width="1593" height="620" alt="Grafana Services" src="https://github.com/user-attachments/assets/d7aaf348-9334-434f-be3a-e8b30a206305" />

Grafana Login Page
<img width="1836" height="986" alt="Grafana Login Page" src="https://github.com/user-attachments/assets/f244825e-3053-460c-bd45-e234ea97dcd8" />


##Week 6 – ECS Services & Application Deployment (Metabase)

What I learned: Running persistent services in ECS, Managing containerized applications and Application-level security

How I accomplished it:I Deployed Metabase on ECS, then Configured ECS services for high availability and Applied security group rules for controlled access.

ECS
<img width="1638" height="481" alt="CSN ECS" src="https://github.com/user-attachments/assets/ae59a3f0-d7c6-4621-a12f-523875247943" />

Cluster
<img width="1624" height="783" alt="CSN Cluster" src="https://github.com/user-attachments/assets/baf026df-82c6-4ccf-9d12-0e9c3ee88690" />

Metabase Secuirty Group
<img width="1638" height="597" alt="CSN Metabase SG" src="https://github.com/user-attachments/assets/0c2acd74-2b84-46a2-8e3e-1bb0f8aa2298" />

Task Definition
<img width="1596" height="882" alt="CSN Task Definietionpng" src="https://github.com/user-attachments/assets/7916c723-9062-4b73-af9c-9cf06bd6eae3" />

Running Cluster
<img width="1605" height="699" alt="Running Cluster" src="https://github.com/user-attachments/assets/afa15180-2e70-4d91-8d87-26e24035cbac" />

Welcome to Metabase Page
<img width="1907" height="989" alt="Setup Page" src="https://github.com/user-attachments/assets/cf198b59-d622-4928-9989-4420ccd9b3ac" />

### Week 7 – Monitoring with Amazon CloudWatch

What I learned: CloudWatch metrics and monitoring, CPU and memory utilization tracking and Observability for containerized workloads

How I accomplished it: I Monitored ECS services using CloudWatch, Analysed CPU utilization metrics and then Verified logs and performance insights

Nginx Cloudwatch
<img width="1906" height="927" alt="nginx cloudwatch" src="https://github.com/user-attachments/assets/b670338d-5299-463c-ad8f-22dfdd267fba" />

CPU Utilization
<img width="1881" height="705" alt="CPUUtilization" src="https://github.com/user-attachments/assets/c0ee0dfb-4ba7-45af-8dea-eb9a0cea5add" />

Nginx Task Definition
<img width="925" height="882" alt="nginx task definition" src="https://github.com/user-attachments/assets/d28f14c9-05ee-4eec-9414-a6622557b7a1" />

Running Service
<img width="1887" height="668" alt="running service" src="https://github.com/user-attachments/assets/a623e2fe-af83-4751-8eb9-3be345d0fb54" />

Welcome to Nginx!
<img width="1900" height="633" alt="Welcome to Nginx" src="https://github.com/user-attachments/assets/beacc106-44d4-47af-91e4-a29e0f6cfeab" />

###v Week 8 – Static Website Hosting (S3 & CloudFront)

What I learned: Hosting static websites on Amazon S3, CloudFront content delivery and Bucket policies and permissions

How I accomplished it: I Uploaded HTML files to an S3 bucket then Configured bucket policies for public access and Set up CloudFront for global content delivery.



Cloudfront Configuration
<img width="1679" height="750" alt="Cloudfront Setup" src="https://github.com/user-attachments/assets/3a4bc269-97f1-4406-87fd-38eb371bbf71" />

HTML File 
<img width="1636" height="405" alt="HTML upload" src="https://github.com/user-attachments/assets/e976993e-cd34-45fc-ab8d-eba1bfed41ce" />

S3 Bucket Properties
<img width="1583" height="878" alt="S3 Bucket Properties" src="https://github.com/user-attachments/assets/6b9e5a6a-6d3c-437d-9980-2f72e51d48aa" />

Website Hosting on AWS
<img width="1884" height="922" alt="Stacey L  Portfolio Stactic Website" src="https://github.com/user-attachments/assets/0452aaed-96d9-459e-bbb4-2f7572434078" />

### Week 9 – Domain, SSL & Secure Hosting

What I learned: Route 53 DNS management, SSL/TLS with AWS Certificate Manager and HTTPS-enabled websites

How I accomplished it: I Registered and configured a domain and Validated an SSL certificate, Linked Route 53, CloudFront, and ACMl, uccessfully deployed a secure HTTPS website.

Route 53
<img width="1610" height="623" alt="route 53 record" src="https://github.com/user-attachments/assets/f797bc7d-e6a3-41ac-a79a-084b6fd6ab49" />

Hosted Zone
<img width="1210" height="706" alt="Hosted Zone" src="https://github.com/user-attachments/assets/18048a86-3609-4e34-9f67-d704de54e9fd" />

SSL Certificate
<img width="1899" height="931" alt="certificate status issed" src="https://github.com/user-attachments/assets/fc317ee7-7acc-4d41-b3ea-4b291019d385" />

Portfolio By StaceyL 
<img width="1895" height="978" alt="portfoliobystaceyl co za" src="https://github.com/user-attachments/assets/fc0f48ea-7259-4cf2-bda2-682351fc407f" />

### Week 10 – Serverless Automation (Lambda, S3, SES)

What I learned: AWS Lambda fundamentals, Event-driven architecture and Logging with CloudWatch, Email notifications using SES

How I accomplished it: I Created an S3-triggered Lambda function (Python) and Configured IAM roles and environment variables. I Integrated Amazon SES for email notifications then I Verified logs and execution via CloudWatch. 

CloudWatch
<img width="1876" height="767" alt="cloudwatch" src="https://github.com/user-attachments/assets/868bd152-2683-4aea-aece-c6aa34c5115b" />

Merics
<img width="1889" height="915" alt="cloudwatch log week 10 task png uploaded" src="https://github.com/user-attachments/assets/4ce04bd0-6040-4f7f-b976-eb07cfdaea46" />

Deployed Python Code
<img width="1912" height="937" alt="depolyed python code" src="https://github.com/user-attachments/assets/94b7e102-2f11-4db0-aac3-30116ba40bea" />

Email Identity Configuration
<img width="1598" height="744" alt="email identity setup" src="https://github.com/user-attachments/assets/53d743fc-1430-4955-b8e6-5a847fd7bc8d" />

Email Verification
<img width="801" height="720" alt="email verification received" src="https://github.com/user-attachments/assets/1c64d150-2d8e-44c6-96c3-74d7dfb6cda4" />

Key Skills Gained

- AWS IAM & Security
- EC2 & VPC Networking
- Containerization with ECS
- Monitoring with CloudWatch
- Static & Secure Web Hosting
- Serverless Architecture (Lambda & SES)

Author
Stacey Munnik
AWS Cloud CSN Bootcamp Graduate (2025)

📌 All screenshots and task evidence are organised by week in this repository.
