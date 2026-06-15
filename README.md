# Evil-AI
AI-Powered Insider Threat Investigation Platform
NightGuard - AI-Powered Insider Threat Investigation Platform
Overview

NightGuard is an AI-powered insider threat investigation platform designed to identify suspicious employee activities that may lead to data breaches or information leakage.

The system analyzes employee behavior, detects anomalies, calculates risk scores, generates investigation reports, and provides security teams with actionable insights through an interactive dashboard.

Problem Statement

Insider threats are one of the most challenging cybersecurity risks faced by organizations.

Employees with legitimate access may intentionally or unintentionally:

Download sensitive data
Use unauthorized USB devices
Access confidential files
Perform suspicious activities during unusual working hours

Traditional monitoring systems often generate alerts without explaining the risk or assisting investigations.

NightGuard addresses this challenge by combining threat detection, behavioral analysis, automated reporting, and AI-assisted investigation.

Key Features
Threat Detection
Large Download Detection
USB Usage Monitoring
Sensitive File Access Detection
Unusual Working Hours Detection
Behavioral Deviation Analysis
Risk Assessment
Employee Risk Scoring
Threat Classification
Low
Medium
High
Critical
Automated Response
Access Suspension Recommendations
Manager Notification Alerts
Alert File Generation
AI Investigation Engine
Threat Classification
Explainable Investigation Reports
Automated Recommendations
Threat Reasoning
Reporting
Evidence Report Generation
Security Summary Report
Employee Investigation Reports
Dashboard
Threat Overview
Risk Score Visualization
Employee Threat Ranking
Critical Threat Monitoring
Threat Timeline
Novelty

NightGuard introduces several innovative features beyond traditional rule-based alert systems.

Behavioral Baseline Analysis

The platform compares current employee activities against historical behavior patterns to identify unusual actions.

Explainable AI Investigation

Rather than only generating alerts, the system explains why an employee was flagged and recommends investigation steps.

Automated Evidence Collection

Evidence reports and investigation documents are automatically generated for security teams.

Threat Prioritization

Employees are ranked according to risk scores, helping analysts focus on the most critical threats first.

System Architecture
Employee Logs
      |
      v
Behavior Analysis Engine
      |
      v
Risk Scoring Engine
      |
      +------------------+
      |                  |
      v                  v
Alert Generator     AI Investigation Engine
      |                  |
      +------------------+
              |
              v
       Evidence Reports
              |
              v
      Streamlit Dashboard
Technology Stack
Programming Language
Python
Data Processing
Pandas
Dashboard Development
Streamlit
Storage
CSV Files
Security Analytics
User Behavior Analysis (UBA)
Risk Scoring Engine
Reporting
Automated Report Generation
Project Structure
NightGuard/
│
├── detector.py
├── dashboard.py
│
├── employee_logs.csv
├── employee_baseline.csv
├── threat_timeline.csv
│
├── evidence_report.csv
├── security_summary.txt
│
├── Bob_alert.txt
├── David_alert.txt
│
├── Bob_AI_Report.txt
├── David_AI_Report.txt
│
└── README.md
Workflow
Employee activity logs are collected.
Behavioral analysis is performed.
Threat indicators are detected.
Risk scores are calculated.
Threat levels are assigned.
AI investigation reports are generated.
Evidence reports are created.
Dashboard visualizes the results.
Results

The system successfully identified high-risk employee activities including:

Large data downloads
USB-based data transfer attempts
Sensitive file access
Behavioral deviations
Suspicious after-hours activity

Automated investigation reports and evidence files were generated for critical-risk employees.

Future Enhancements
Real-time Monitoring
Machine Learning-Based Anomaly Detection
Email Notifications
Mobile Alerts
SIEM Integration
Cloud Deployment
Predictive Threat Intelligence
Advanced User Behavior Analytics
Team

NightGuard was developed as a cybersecurity hackathon project focused on insider threat detection and investigation automation.
