# AWS 3-Tier Web Application Infrastructure as Code Project

## Overview

This project was developed as part of the System Administration Track at the Information Technology Institute (ITI).

The objective was to design, deploy, and automate a production-style 3-Tier Web Application on Amazon Web Services (AWS) using Infrastructure as Code (IaC) and configuration management tools, following AWS best practices for scalability, security, automation, and high availability.

## Architecture Highlights

- Custom VPC Design
- Public and Private Subnets across Multiple Availability Zones
- Internet Gateway and NAT Gateway Configuration
- External and Internal Application Load Balancers (ALBs)
- Auto Scaling Groups for Frontend and Backend Tiers
- Secure Bastion Host for Administrative Access
- MongoDB Replica Set for High Availability and Data Replication
- Dynamic Inventory using Ansible AWS EC2 Plugin
- Nginx Reverse Proxy Configuration
- Node.js Backend Deployment with PM2
- HashiCorp Vault for Secrets Management
- Security Groups Implementing Least Privilege Access
- Fully Automated Provisioning and Configuration Pipeline

## Technologies Used

- Amazon Web Services (AWS)
- Terraform
- Ansible
- Linux
- Nginx
- Node.js
- PM2
- MongoDB
- HashiCorp Vault

## Key Objectives

- High Availability
- Scalability
- Automation
- Security
- Fault Tolerance

## Project Structure

```text
├── terraform/
├── ansible/
├── nginx/
├── mongodb/
├── vault/
├── scripts/
└── documentation/
