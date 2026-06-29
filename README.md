# 🚨 AWS CloudWatch Monitoring & SNS Alerting System (Project 7)

A real-time cloud monitoring and alerting system built using AWS CloudWatch and SNS. This project demonstrates how an EC2 instance can be monitored for CPU usage and automatically trigger email alerts when thresholds are exceeded.

---

## 🚀 Project Overview

This project implements an automated monitoring and alerting system on AWS.

An EC2 instance is monitored using **Amazon CloudWatch metrics**.  
When CPU utilization exceeds a defined threshold, a **CloudWatch alarm is triggered**, which sends a notification via **Amazon SNS (email alert)**.

This simulates real-world DevOps observability and incident response systems.

---

## 🏗️ Architecture Diagram

![Architecture Diagram](screenshots/architecture-diagram.png)

---

## ☁️ AWS Services Used

| Service | Purpose |
|----------|----------|
| Amazon EC2 | Runs Linux instance for CPU load testing |
| Amazon CloudWatch | Monitors CPU metrics and triggers alarms |
| Amazon SNS | Sends email notifications |
| IAM | Manages permissions |

---

## 📁 Project Structure
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

---

## ✨ Features

- EC2 CPU monitoring using CloudWatch
- Threshold-based alarm configuration
- Real-time email alerts using SNS
- Linux stress testing for load simulation
- End-to-end AWS monitoring pipeline
- Fully automated alerting system
- AWS Free Tier compatible setup

---

## 📸 Implementation Screenshots

---

### 🖥️ EC2 Instance Running

![EC2 Instance Running](screenshots/ec2-instance-running.png)

---

### 📊 CloudWatch Alarm Created

![CloudWatch Alarm Created](screenshots/cloudwatch-alarm-created.png)

---

### ⚙️ Alarm Configuration Details

![Alarm Configuration](screenshots/alarm-configuration-details.png)

---

### 📢 SNS Topic Created

![SNS Topic Created](screenshots/sns-topic-created.png)

---

### 📬 SNS Subscription Confirmed

![SNS Subscription Confirmed](screenshots/sns-subscription-confirmed.png)

---

### 🔐 EC2 SSH Connection

```bash
ssh -i your-key.pem ec2-user@<public-ip>
🔥 CPU Stress Test Running
stress --cpu 2 --timeout 300
🚨 CloudWatch Alarm Triggered

📩 SNS Email Notification

✅ Alarm Back to OK State

🎯 Key Learnings
-AWS CloudWatch monitoring and metrics
-Alarm creation and threshold tuning
-SNS email notification system
-EC2 performance stress testing
-Real-time cloud observability
-End-to-end monitoring pipeline

💰 Cost Optimization
-Uses AWS Free Tier services only
-EC2 t2.micro instance
-CloudWatch free monitoring
-SNS free email notifications

🧹 Cleanup Performed
-CloudWatch alarm deleted
-SNS topic and subscription removed
-EC2 instance terminated

👨‍💻 Author

Jeet Zala
AWS Cloud & DevOps Portfolio Project
