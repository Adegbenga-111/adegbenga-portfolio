# Adegbenga Cloud & Security Portfolio

## Adelaja Oluwagbenga Ayomide

**Junior Cloud Engineer | Cloud Support | Security-Focused Infrastructure**

<a href="https://www.linkedin.com/in/gbenga-adelaja-8a2173211">LinkedIn</a>

---

## Executive Summary

I am a Computer Science graduate with hands-on experience designing, deploying, securing, and supporting cloud-based and networked systems. My work focuses on **AWS cloud infrastructure, security best practices, monitoring, and troubleshooting**, with supporting knowledge of Azure fundamentals and enterprise firewall technologies.

I build real-world, production-style projects that simulate operational responsibilities such as access control, secure networking, incident investigation, system reliability, and application troubleshooting. I am actively seeking an **entry-level Cloud Support or Junior Cloud Engineer role**, with a long-term interest in cloud security.

---

## Core Skills

### Cloud & Infrastructure
- AWS: EC2, VPC, IAM, S3, CloudFront, Route 53, ACM, RDS, CloudWatch
- Secure public and private subnet design
- NAT gateway and bastion-style access patterns
- Load-balanced and decoupled application architectures

### Security & Networking
- IAM least-privilege access control
- Network isolation using security groups
- HTTPS enforcement and TLS certificate management
- FortiGate firewall configuration (interfaces, routing, NAT, policies)
- VPN and VLAN network design (simulated environments)

### Monitoring & Troubleshooting
- Cloud deployment debugging and issue resolution
- SSH, permission, and connectivity troubleshooting
- Network routing and database access diagnosis
- Log-based investigation and validation

---

## Featured Projects

### 🐳 Multi-Container Web Application with Docker & Docker Compose (DevOps – Phase 4 Project 1)

Designed and implemented a **production-style, multi-container web application** using Docker and Docker Compose, focusing on service orchestration, container networking, and real-world troubleshooting.

**Architecture Overview**
- Nginx frontend container serving static HTML and CSS
- PHP 8.2 (Apache) backend API container
- MySQL 8.0 database container with persistent storage
- phpMyAdmin container for database administration
- Custom Docker bridge network for secure service-to-service communication
- Nginx reverse proxy routing `/api` requests to the backend service

**Key Outcomes**
- Orchestrated multiple services using Docker Compose with a shared network
- Implemented reverse proxying to decouple frontend and backend services
- Solved database startup race conditions using retry logic
- Debugged container DNS and service discovery issues
- Resolved YAML formatting, path resolution, and environment variable issues
- Applied production-style practices such as not exposing database ports to the host

**DevOps Concepts Demonstrated**
- Containerization and multi-service orchestration
- Service discovery using Docker DNS
- Environment variable management with `.env`
- Reverse proxy configuration using Nginx
- Persistent data storage using Docker volumes
- Troubleshooting startup order, networking, and configuration issues

[View Project](https://github.com/Adegbenga-111/Multi-Container-Web-Application)

### 🚀 Production-Grade 3-Tier Web Application on AWS

Designed and deployed a **production-style 3-tier web application architecture** with strict network isolation, HTTPS security, and monitoring.

**Architecture Overview**
- Custom VPC with public and private subnets
- Application Load Balancer handling HTTPS traffic
- Backend EC2 instances in private subnets
- PostgreSQL RDS deployed in private DB subnets
- Static frontend hosted on S3 and served via CloudFront
- Route 53 for DNS and ACM for TLS certificates
- CloudWatch monitoring and VPC Flow Logs

**Key Outcomes**
- Implemented secure frontend → backend → database communication
- Debugged EC2-to-RDS connectivity using security groups
- Resolved CORS and browser-based API errors
- Enforced HTTPS end-to-end using ACM and ALB
- Applied real-world troubleshooting and validation techniques

[View Project](https://github.com/Adegbenga-111/Production-Grade-3-Tier-Web-Application-on-AWS-using-EC2)

---

### AWS Public & Private Network Deployment

Secure VPC architecture with structured CIDR planning, public and private subnets, bastion-style access, NAT gateway routing, and least-privilege security groups.

- Designed custom VPC with controlled traffic flow
- Isolated private EC2 instances from public internet access
- Troubleshot routing and connectivity failures

[View Project](https://github.com/Adegbenga-111/AWS-Public-Private-Deployment)

---

### Static Website Hosting with S3 & CloudFront

Deployed a globally distributed static website using Amazon S3 and CloudFront with secure access controls and HTTPS enforcement.

- Implemented private S3 bucket access
- Configured CloudFront for global content delivery
- Resolved access-denied and permission-related issues

[View Project](https://github.com/Adegbenga-111/Creating-a-Static-Website-with-S3-Hosting-and-Cloudfront-)

---

### Web Application Deployment with EC2 & DynamoDB

Deployed a PHP web application on EC2 using IAM roles and AWS SDK for secure, programmatic access to DynamoDB.

- Implemented IAM role-based access (no static credentials)
- Designed stateless application architecture
- Practiced cloud troubleshooting and service integration

[View Project](https://github.com/Adegbenga-111/Building-a-web-app-with-EC2-and-DynamoDB)

---

### FortiGate Firewall: Secure Internet Access

Simulated an enterprise network secured using FortiGate firewall policies, NAT configuration, and routing control.

- Configured firewall interfaces and routes
- Implemented NAT for controlled internet access
- Applied core cybersecurity and networking concepts

[View Project](https://github.com/Adegbenga-111/Enabling-Secure-Internet-Access-via-FortiGate-Firewall-in-a-Simulated-Network)

---

## Security & Analysis Projects

- **Email Phishing Analysis Playbook**  
  Practical playbook for analyzing phishing emails and identifying malicious indicators.  
  [View Project](https://github.com/Adegbenga-111/Play-book-for-Email-Analysis-For-Phishing-Activities)

- **Machine Learning for Phishing Detection**  
  Built and evaluated ML models using Python (Random Forest, MLP) for phishing detection in a research context.

---

## Tools & Technologies

### Networking & Traffic Analysis
- Packet Tracer
- Wireshark
- Snort

### Endpoint & SIEM
- Microsoft Defender for Endpoint
- Microsoft Sentinel
- Splunk
- Elastic Stack

### Development & Research
- Google Colab

---

## Certifications

- Microsoft Azure Fundamentals (AZ-900)
- Fortinet Certified Fundamentals in Cybersecurity (FCF)
- Fortinet Certified Associate in Cybersecurity (FCA)

---

## Career Focus

I am building toward a career in **cloud operations and security-focused infrastructure**, with an emphasis on system reliability, access control, monitoring, and incident response. My goal is to grow from a **Cloud Support or Junior Cloud Engineer** role into cloud security or platform engineering responsibilities.

---

*This portfolio reflects the latest, production-ready state of my work. Earlier learning iterations and experiments are preserved within individual project repositories to demonstrate growth over time.*
