# Secure EC2 Web Server Deployment

Easily deploy and secure a web server on AWS EC2 using VPC, subnets, firewalls, and NACLs. Built for cloud and DevOps enthusiasts eager to learn AWS hands-on with real architectures and full network protection.

---

## Features

- Deploy a web server on AWS EC2 within a secure environment
- Configure VPCs, custom subnets, internet gateways, security groups, and NACLs
- Set precise inbound/outbound firewall rules for HTTP, HTTPS, and SSH
- Step-by-step cloud networking designed for learning and real-world application[file:2]

## Architecture Overview

- **VPC**: Isolated networking environment built specifically for the project
- **Public Subnet**: Hosts the EC2 web server with an auto-assigned public IP
- **Internet Gateway**: Provides external access and routing capabilities
- **Security Group**: Configured for HTTP, HTTPS, and SSH access control
- **Network ACLs**: Adds enhanced network traffic filtering and security

## Setup Instructions

1. **Clone this repository**
   ```
   git clone https://github.com/ShaikhAteeb02/Secure-EC2-Web-Server.git
   cd Secure-EC2-Web-Server
   ```
2. **Follow the setup guide**
   - Navigate through AWS Console to create VPC, subnets, and internet gateway
   - Configure your EC2 instance with the provided Security Group and NACLs
3. **Deploy and verify**
   - Launch your instance using Amazon Linux or Ubuntu with Apache installed
   - Access via SSH and verify with your public IP in a browser

## Usage

- Great for AWS networking and security learning
- Can be extended to include load balancers or private routing
- Use it as a base architecture for cloud-based web deployments

---

## Connect With Me

<p align="center">
  <a href="https://github.com/ShaikhAteeb02" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-ShaikhAteeb02-181717?logo=github&style=for-the-badge" alt="GitHub Button"/>
  </a>
  <a href="https://www.linkedin.com/in/ateeb-ahmed-shaikh-932234192/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Ateeb--Ahmed--Shaikh-0077B5?logo=linkedin&style=for-the-badge" alt="LinkedIn Button"/>
  </a>
</p>

> Made with dedication to cloud and DevOps learning by [Ateeb Ahmed Shaikh](https://github.com/ShaikhAteeb02)
