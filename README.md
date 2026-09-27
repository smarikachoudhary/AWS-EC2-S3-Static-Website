# AWS EC2 & S3 Static Website Hosting

## Project Objective
Launch an EC2 instance, install Nginx Web Server, create an S3 bucket, upload website backup files to S3, and access the website using the EC2 Public IP.

## Architecture
User -> EC2 Instance (Nginx Web Server) -> S3 Bucket (Backup Storage)

## AWS Services Used
- Amazon EC2 (Amazon Linux 2023, t3.micro)
- Amazon S3
- Nginx Web Server
- Security Groups

## Steps Performed

### 1. Launch EC2 Instance
Created an EC2 instance using Amazon Linux 2023, t3.micro, with Security Group allowing ports 22 (SSH) and 80 (HTTP).

### 2. Connect to EC2
Connected using EC2 Instance Connect (SSH) with key pair authentication.

### 3. Install Nginx   

### 4. Create Website
Created `/usr/share/nginx/html/index.html` with custom content and verified using the EC2 public IP.

### 5. Create S3 Bucket
Created a unique S3 bucket (`smarika-website-backup-2026`) and uploaded website backup files.

## Deliverables
Screenshots attached in this repository showing:
- EC2 Instance Running
- Security Group Configuration
- Live Website in Browser
- S3 Bucket Created
- File Uploaded to S3

## Learning Outcomes
- Understanding of EC2 instance creation and configuration
- Nginx web server installation and setup
- S3 bucket creation and file management
- Security Group (firewall) configuration
- AWS basics and cloud hosting concepts

## Author
Smarika Choudhary
