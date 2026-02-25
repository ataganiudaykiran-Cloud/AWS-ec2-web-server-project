# AWS EC2 Web Server Project 🚀

## Project Overview
This project demonstrates how to launch an EC2 instance on AWS and host a custom web page using Apache Web Server.

## Services Used
- AWS EC2
- Amazon Linux 2
- Security Groups
- Apache HTTP Server

## Steps Performed
1. Launched EC2 instance (t3.micro - Free Tier)
2. Configured Security Group (Allowed SSH - Port 22, HTTP - Port 80)
3. Installed Apache Web Server
4. Created custom HTML webpage
5. Accessed website using Public IP

## Commands Used
sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd

## Outcome
Successfully hosted a custom webpage on AWS EC2.

## learning Outcome
-understanding EC2
-Security Groups configuration
-Linux command usage
-Web server deployment

# AWS-ec2-web-server-project
Deployed a web server on AWS EC2 using Amazon Linux and Apache. Configured security groups, installed HTTP server, and hosted a custom HTML webpage.
