# 🚨 AWS CloudWatch Monitoring & SNS Alerting System - Project 7

![AWS](https://img.shields.io/badge/AWS-Cloud%20Services-orange)
![CloudWatch](https://img.shields.io/badge/Monitoring-CloudWatch-blue)
![SNS](https://img.shields.io/badge/Notification-SNS-red)
![EC2](https://img.shields.io/badge/Compute-EC2-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview

This project demonstrates a **real-time monitoring and alerting system** using AWS services.

An EC2 instance is continuously monitored using **Amazon CloudWatch**, and when CPU usage exceeds a threshold, an alert is triggered via **Amazon SNS (email notification)**.

---

## 🏗️ Architecture Diagram


EC2 Instance
↓
CloudWatch Metrics (CPU Utilization)
↓
CloudWatch Alarm
↓
SNS Topic
↓
Email Notification


📌 Architecture Image (optional):

architecture-diagram.png


---

## 🎯 Objective

- Monitor EC2 CPU utilization in real time
- Configure CloudWatch alarms with thresholds
- Trigger alerts using SNS email notifications
- Simulate high CPU load using stress testing
- Build end-to-end AWS monitoring pipeline

---

## 🧰 AWS Services Used

- Amazon EC2
- Amazon CloudWatch
- Amazon SNS (Simple Notification Service)
- Amazon Linux (SSH access)

---

## ⚙️ Implementation Steps

### 1. EC2 Instance Running
**Screenshot:** `ec2-instance-running.png`  
EC2 instance successfully launched and running.

---

### 2. CloudWatch Alarm Created
**Screenshot:** `cloudwatch-alarm-created.png`  
CloudWatch alarm configured for CPUUtilization metric.

---

### 3. Alarm Configuration
**Screenshot:** `alarm-configuration-details.png`  
Threshold, evaluation period, and conditions defined.

---

### 4. SNS Topic Created
**Screenshot:** `sns-topic-created.png`  
SNS topic created for email notifications.

---

### 5. SNS Subscription Confirmed
**Screenshot:** `sns-subscription-confirmed.png`  
Email subscription successfully confirmed.

---

### 6. EC2 SSH Connection
**Screenshot:** `ec2-ssh-connected.png`  

```bash
ssh -i your-key.pem ec2-user@<public-ip>
7. CPU Stress Test

Screenshot: cpu-stress-test-running.png

stress --cpu 2 --timeout 300
8. CloudWatch Alarm Triggered

Screenshot: cloudwatch-alarm-triggered.png
Alarm state changed to ALARM due to high CPU usage.

9. SNS Email Notification

Screenshot: sns-email-notification.png
Email alert successfully received.

10. Alarm Back to OK State

Screenshot: alarm-back-to-ok.png
CPU normalized and alarm returned to OK state.

📁 Screenshot Directory Structure
/screenshots
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
📊 Key Learnings
AWS CloudWatch monitoring & metrics
Alarm creation & threshold tuning
SNS email notification system
EC2 performance testing using stress tool
Real-time cloud observability pipeline
🚀 Outcome

✔ Fully functional monitoring system
✔ Real-time CPU-based alerting
✔ Email notification system working
✔ Hands-on AWS DevOps observability experience

👨‍💻 Author

Jeet Zala
AWS Cloud & DevOps Portfolio Project
