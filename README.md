
# 🔐 AWS Secrets Monitoring & Alerting System

## 📌 Overview
This project demonstrates a real-time cloud security monitoring system designed to track and alert on access to sensitive data using AWS services.

The system focuses on monitoring AWS Secrets Manager activity and generating alerts when secrets are accessed, helping detect unauthorized or suspicious behavior.

---
<img width="2956" height="1108" alt="image" src="https://github.com/user-attachments/assets/2430d598-3170-496d-8507-c608a2de01d8" />


## 🧱 Architecture
The system follows an event-driven monitoring approach:

User / Application  
        ↓  
AWS Secrets Manager (Secret Access)  
        ↓  
AWS CloudTrail (Logs API Activity)  
        ↓  
Amazon CloudWatch Logs (Monitoring & Filtering)  
        ↓  
CloudWatch Alarm (Trigger on Suspicious Activity)  
        ↓  
Amazon SNS (Real-Time Alerts)  
        ↓  
Email Notification  

---

## ⚙️ Services Used
- AWS Secrets Manager – Stores sensitive credentials securely  
- AWS CloudTrail – Captures API activity and access logs  
- Amazon CloudWatch – Monitors logs and creates alarms  
- Amazon SNS – Sends real-time notifications  
- Amazon S3 – Stores CloudTrail logs  

---

## 🔍 Features
- Real-time monitoring of secret access events  
- Detection of unauthorized or unusual access attempts  
- Automated alert generation using SNS  
- Event-driven architecture for faster incident response  
- Improved visibility into sensitive data usage  

---

## 🚨 Use Cases
- Detect unauthorized access to credentials  
- Monitor API usage of sensitive resources  
- Alert on abnormal access patterns  
- Track root or privileged account activity  

---

## 🛠️ Setup Steps
1. Enable AWS CloudTrail and configure logging  
2. Enable logging for AWS Secrets Manager events  
3. Send logs to CloudWatch Logs  
4. Create metric filters for secret access events  
5. Configure CloudWatch alarms  
6. Set up SNS topic and email subscription  
7. Test alert by accessing a secret  

---

## 📊 Sample Alerts
- Secret accessed by unauthorized IAM user  
- Multiple access attempts in a short time  
- Access from unusual region or IP  

---

## 🛡️ Security Benefits
- Faster detection of security incidents  
- Automated alerting reduces manual monitoring  
- Improved compliance and audit visibility  
- Enhanced protection of sensitive data  

---




## 🚀 Skills Gained
- Cloud Security Monitoring  
- AWS Logging & Alerting  
- Incident Detection & Response  
- Event-driven Security Architecture  

