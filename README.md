# 🌐 2-Tier Architecture on AWS  
### Using Route 53, EC2, Load Balancer, Auto Scaling, CloudFront & WAF

This project demonstrates the implementation of a **secure, scalable, and highly available 2-tier web application architecture on AWS**.  
The complete step-by-step implementation is available in the uploaded **PDF document** in this repository.

---

## 📌 Architecture Overview

**Traffic Flow:**

User → Route 53 → CloudFront → WAF → Application Load Balancer → EC2 (Auto Scaling)

### 🏗️ Tier Details

### ✅ Tier 1 – Web / Presentation Tier
- Amazon Route 53 (DNS)
- Amazon CloudFront (CDN)
- AWS Web Application Firewall (WAF)
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- EC2 Web Servers

### ✅ Tier 2 – Application / Backend Tier
- Application running on private EC2 instances  
- (Optional: Can be extended to RDS for database layer)

---

## 🔧 AWS Services Used

- ✅ Amazon EC2
- ✅ Auto Scaling Group
- ✅ Application Load Balancer
- ✅ Amazon Route 53
- ✅ Amazon CloudFront
- ✅ AWS WAF
- ✅ IAM
- ✅ VPC, Subnets, Security Groups

---

## 🛡️ Key Features

- ✅ High Availability using Multi-AZ setup
- ✅ Automatic Scaling using Auto Scaling Group
- ✅ Global Content Delivery using CloudFront
- ✅ DDoS & Web Attack Protection using AWS WAF
- ✅ Secure Architecture using Private Subnets & Security Groups
- ✅ Custom Domain using Route 53

---

## 📄 Project Documentation

📘 **Full Implementation Guide Available in PDF:**

