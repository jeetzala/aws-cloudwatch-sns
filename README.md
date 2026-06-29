# 🚨 AWS CloudWatch Monitoring & SNS Alerting System

A real-time cloud monitoring and alerting system built using AWS services.  
This project demonstrates how to monitor EC2 instance performance using Amazon CloudWatch and automatically send alerts using Amazon SNS when CPU utilization exceeds a defined threshold.

---

## 🚀 Project Overview

This project implements a fully functional monitoring and alerting pipeline on AWS.

The EC2 instance is continuously monitored using CloudWatch metrics.  
When CPU utilization exceeds a defined threshold, CloudWatch triggers an alarm and sends a notification via SNS (email).

This simulates a real-world production monitoring system used in DevOps environments.

---

## 🏗️ Architecture Diagram


EC2 Instance → CloudWatch Metrics → CloudWatch Alarm → SNS Topic → Email Notification


📸 Architecture Screenshot:
`screenshots/architecture-diagram.png`

---

## ☁️ AWS Services Used

| Service | Purpose |
|----------|----------|
| Amazon EC2 | Compute instance for testing CPU load |
| Amazon CloudWatch | Monitoring CPU metrics and alarms |
| Amazon SNS | Sending email notifications |
| IAM | Permissions and access control |

---

## 📁 Project Structure

```text
aws-cloudwatch-sns-project-7/
│
├── README.md
└── screenshots/
    ├── ec2-instance-running.png
    ├── cloudwatch-alarm-created.png
    ├── alarm-configuration-details.png
    ├── sns-topic-created.png
    ├── sns-subscription-confirmed.png
    ├── ec2-ssh-connected.png
    ├── cpu-stress-test-running.png
    ├── cloudwatch-alarm-triggered.png
    ├── sns-email-notification.png
    ├── alarm-back-to-ok.png
    └── architecture-diagram.png
✨ Features
EC2 instance monitoring using CloudWatch
CPU utilization-based alarm configuration
Real-time email notifications using SNS
Stress testing using Linux stress tool
End-to-end cloud monitoring workflow
Fully automated alerting system
AWS Free Tier compatible setup
📸 Implementation Screenshots
🖥️ EC2 Instance Setup
EC2 Instance Running

screenshots/ec2-instance-running.png

📊 CloudWatch Configuration
CloudWatch Alarm Created

screenshots/cloudwatch-alarm-created.png

Alarm Configuration Details

screenshots/alarm-configuration-details.png

📢 SNS Setup
SNS Topic Created

screenshots/sns-topic-created.png

SNS Subscription Confirmed

screenshots/sns-subscription-confirmed.png

🔐 EC2 Access
SSH Connection Established

screenshots/ec2-ssh-connected.png

ssh -i your-key.pem ec2-user@<public-ip>
🔥 Load Testing
CPU Stress Test Running

screenshots/cpu-stress-test-running.png

stress --cpu 2 --timeout 300
🚨 Alerting System
CloudWatch Alarm Triggered

screenshots/cloudwatch-alarm-triggered.png

SNS Email Notification Received

screenshots/sns-email-notification.png

✅ Recovery State
Alarm Back to OK State

screenshots/alarm-back-to-ok.png

🔄 Workflow
Developer
   │
   ▼
EC2 Instance (CPU Load)
   │
   ▼
CloudWatch Metrics
   │
   ▼
CloudWatch Alarm Triggered
   │
   ▼
SNS Topic
   │
   ▼
Email Notification
🎯 Skills Demonstrated
AWS
Amazon EC2
Amazon CloudWatch
Amazon SNS
IAM Roles & Permissions
DevOps
Monitoring & Alerting
Infrastructure Observability
Incident Simulation
Real-time Notification Systems
Cloud Engineering
Performance Monitoring
Threshold-based Alerting
Linux-based Load Testing
Cloud Architecture Design
💰 Cost Optimization

This project is fully compatible with AWS Free Tier.

Used services:

EC2 (t2.micro)
CloudWatch
SNS

💡 Always stop or terminate resources after testing to avoid charges.

🧹 Cleanup Steps

To avoid unnecessary billing:

Delete CloudWatch Alarm
Delete SNS Topic & Subscription
Stop/Terminate EC2 Instance
Remove unused IAM roles (if any)
📚 Key Learnings
AWS monitoring architecture
CloudWatch alarm configuration
SNS email-based alerting system
Real-time system monitoring
Linux CPU stress testing
End-to-end DevOps observability pipeline
👨‍💻 Author

Jeet Zala

Aspiring Cloud & DevOps Engineer focused on AWS, automation, and cloud infrastructure.
