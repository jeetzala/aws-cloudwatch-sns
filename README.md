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


![Architecture Diagram](screenshots/architecture-diagram.png)


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
![EC2 Instance Running](screenshots/ec2-instance-running.png)
EC2 instance successfully launched and running.

---

### 2. CloudWatch Alarm Created
![CloudWatch Alarm Created](screenshots/cloudwatch-alarm-created.png)
CloudWatch alarm configured for CPUUtilization metric.

---

### 3. Alarm Configuration
![Alarm Configuration](screenshots/alarm-configuration-details.png)  
Threshold, evaluation period, and conditions defined.

---

### 4. SNS Topic Created
![SNS Topic Created](screenshots/sns-topic-created.png)
SNS topic created for email notifications.

---

### 5. SNS Subscription Confirmed
![SNS Subscription Confirmed](screenshots/sns-subscription-confirmed.png)
Email subscription successfully confirmed.

---

### 6. EC2 SSH Connection
![SNS Subscription Confirmed](screenshots/ec2-ssh-connected.png)
Connection Successful

### 7. CPU Stress Test
![SNS Subscription Confirmed](screenshots/cpu-stress-test-running.png)
stress --cpu 2 --timeout 300

### 8. CloudWatch Alarm Triggered
![SNS Subscription Confirmed](screenshots/cloudwatch-alarm-triggered.png)
Alarm state changed to ALARM due to high CPU usage.

### 9. SNS Email Notification
![SNS Subscription Confirmed](screenshots/sns-email-notification.png)
Email alert successfully received.

### 10. Alarm Back to OK State
![SNS Subscription Confirmed](screenshots/alarm-back-to-ok.png)
CPU normalized and alarm returned to OK state.

---

## 💰 Cost Optimization
- Uses AWS Free Tier services only
- EC2 t2.micro instance
- CloudWatch free tier monitoring
- SNS free email notifications

---
 
## 🎯 Key Skills Learned
- AWS CloudWatch Monitoring
- Alarm Configuration & Threshold Setup
- SNS Email Notification System
- EC2 Performance Testing
- Linux Stress Testing
- Real-time Cloud Observability Pipeline

---

## 🚀 Outcome

 ✔ Fully functional monitoring system
 ✔ Real-time CPU-based alerting
 ✔ Email notification system working
 ✔ Hands-on AWS DevOps observability experience

 ---

 ## 🧹 Cleanup Steps
- Delete CloudWatch Alarm
- Delete SNS Topic and Subscription
- Stop or terminate EC2 instance

---

## 👨‍💻 Author

Jeet Zala
AWS Cloud & DevOps Portfolio Project
