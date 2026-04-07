# 🔐 DVWA Lab 01 – Information Security (Brute Force Attack)

## 📚 Course Information
**Course:** Information Security (BERR 3123)  
**Semester:** 1 2025/2026  
**Lab:** DVWA X1 – Password Brute Force Attack  

---

## 📌 Overview
This lab focuses on understanding web application vulnerabilities using Damn Vulnerable Web Application (DVWA).

The main objectives are:
- Perform password brute force attacks
- Analyze network traffic using Wireshark/tcpdump
- Understand attack surfaces, threats, and impacts
- Explore security mitigation techniques

---

## 🎯 Objectives
- Understand brute force attack mechanisms
- Use tools such as:
  - Burp Suite
  - wfuzz
  - Wireshark / tcpdump
- Analyze HTTP traffic and authentication behavior
- Evaluate system weaknesses based on CIA triad:
  - Confidentiality
  - Integrity
  - Availability

---

## 🛠️ Tools & Technologies
- DVWA (Damn Vulnerable Web Application)
- WSL2 Ubuntu 20.04
- Apache2 Web Server (Port 80)
- MariaDB (Port 3306)
- Kali Linux (Attacker machine)
- Burp Suite (Community Edition)
- Wireshark / tcpdump
- wfuzz

---

## ⚙️ Environment Setup

### 1. Install WSL2 + Ubuntu
Install Ubuntu 20.04 via Microsoft Store and configure WSL2.

### 2. Install Required Packages
```bash
sudo apt update
sudo apt install -y apache2 mariadb-server mariadb-client php php-mysqli php-gd libapache2-mod-php
