# 🚨 AWS CloudWatch Monitoring & SNS Alerting System (Project 7)

![AWS](https://img.shields.io/badge/AWS-Cloud%20Monitoring-orange)
![CloudWatch](https://img.shields.io/badge/CloudWatch-Alarm-blue)
![SNS](https://img.shields.io/badge/SNS-Email%20Alerts-red)
![EC2](https://img.shields.io/badge/EC2-Compute-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview

This project demonstrates a real-time AWS monitoring and alerting system using **Amazon CloudWatch and Amazon SNS**.

An EC2 instance is monitored for CPU utilization, and when usage exceeds a threshold, an automatic email alert is triggered.

---

## 🏗️ Architecture Diagram

![Architecture Diagram](screenshots/architecture-diagram.png)

---

## ☁️ AWS Services Used

| Service | Purpose |
|----------|----------|
| Amazon EC2 | Runs Linux instance for CPU testing |
| Amazon CloudWatch | Monitors CPU metrics and triggers alarms |
| Amazon SNS | Sends email notifications |
| IAM | Manages permissions |

---

## 🚀 Project Workflow


EC2 Instance
↓
CloudWatch Metrics (CPU Utilization)
↓
CloudWatch Alarm
↓
SNS Topic
↓
Email Notification


---

## ⚙️ Implementation Steps

---

### 1. EC2 Instance Running

![EC2 Instance](screenshots/ec2-instance-running.png)

---

### 2. CloudWatch Alarm Created

![CloudWatch Alarm](screenshots/cloudwatch-alarm-created.png)

---

### 3. Alarm Configuration Details

![Alarm Configuration](screenshots/alarm-configuration-details.png)

---

### 4. SNS Topic Created

![SNS Topic](screenshots/sns-topic-created.png)

---

### 5. SNS Subscription Confirmed

![SNS Subscription](screenshots/sns-subscription-confirmed.png)

---

### 6. EC2 SSH Connection

```bash id="q2k1aa"
ssh -i your-key.pem ec2-user@<public-ip>

7. CPU Stress Test Running
stress --cpu 2 --timeout 300

8. CloudWatch Alarm Triggered

9. SNS Email Notification Received

10. Alarm Back to OK State

📁 Screenshot Folder Structure
screenshots/
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
🎯 Key Skills Learned
AWS CloudWatch Monitoring
Alarm Configuration & Threshold Setup
SNS Email Notification System
EC2 Performance Testing
Linux Stress Testing
Real-time Cloud Observability Pipeline
💰 Cost Optimization
Uses AWS Free Tier services only
EC2 t2.micro instance
CloudWatch free tier monitoring
SNS free email notifications
🧹 Cleanup Steps
Delete CloudWatch Alarm
Delete SNS Topic and Subscription
Stop or terminate EC2 instance
👨‍💻 Author

Jeet Zala

AWS Cloud & DevOps Portfolio Project
