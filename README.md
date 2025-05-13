# aws-3tier-webapp
# 🧱 AWS 3-Tier Web Application Architecture with Auto Scaling and RDS (Hands-on Deployment)

This project demonstrates the deployment of a scalable and highly available 3-tier architecture on AWS. It is ideal for cloud beginners, DevOps learners, and portfolio building.

---

## 📌 Project Overview

This architecture includes:

- ✅ VPC with 8 subnets across 2 Availability Zones
- ✅ Application Load Balancer (ALB) for routing traffic
- ✅ Auto Scaling Group with EC2 instances for Web and App tiers
- ✅ Amazon RDS (MariaDB) in private subnets for the Database tier
- ✅ Custom AMIs for consistent EC2 provisioning
- ✅ Proper route table and security group configurations

---

## 🔧 Tech Stack

| Layer       | Components                             |
|-------------|----------------------------------------|
| Cloud       | AWS (EC2, RDS, VPC, ALB, ASG, NAT)     |
| OS          | Amazon Linux 2                         |
| Web Server  | NGINX                                  |
| App Code    | PHP                                    |
| DB Engine   | MariaDB (Amazon RDS)                   |
| Automation  | Launch Templates, Custom AMIs          |
| Monitoring  | Amazon CloudWatch                      |

---


---

## 🚀 Features

- Multi-AZ high availability
- Auto Scaling based on CPU metrics
- Secure architecture with private DB subnets
- Reusable and scalable infrastructure
- Custom AMIs for consistent EC2 configuration
- CloudWatch monitoring and health checks

---

## 📸 Demo Videos (1)

- Load Balancer & Auto Scaling behavior demonstration
- VPC & Subnet layout, IGW setup, RDS configuration


https://github.com/user-attachments/assets/c77484b3-2ef7-498f-be6c-a1ae932b022e



## 👨‍💻 Author

Created by Vishal Bobhate  
📧 Email: bobhatev13@gmail.com  
🔗 GitHub: [@bobhatevishal](https://github.com/bobhatevishal)  
🔗 LinkedIn: [linkedin.com/in/vishal-bobhate](https://www.linkedin.com/in/vishal-bobhate)

---


