# 🛡️ Home Cybersecurity Lab & Threat Detection

Welcome to my personal cybersecurity lab project designed to simulate real-world attacks and practice SOC analyst skills. This setup focuses on threat detection, log analysis, and incident response using industry-standard tools and frameworks.

---

## 🔧 Lab Setup

### 💻 Virtual Machines (via VMware Workstation)

* **Attack Box**: Kali Linux
* **Target Machines**:

  * Metasploitable 2
  * Windows 10 with Elastic Agent installed

### 🌐 Monitoring Stack

* **Elastic Cloud (ELK Stack)**:

  * Elasticsearch
  * Logstash
  * Kibana
* **Elastic Agent**:

  * Installed on Windows VM
  * Monitors system logs, endpoint activity, and security events

---

## ⚔️ Simulated Attacks

### 🧪 Brute-Force Login Simulation

* Custom PowerShell script mimicking login attempts
* Triggered detection rules in Kibana's SIEM

### 🛠️ Nmap & Metasploit

* Conducted network scans and exploits from Kali to Metasploitable
* Captured traffic using Wireshark for analysis
* Verified detection and alerting capabilities

---

## 📈 Detection Rules & Analysis

### ✅ Elastic SIEM

* Built custom detection rules using the Kibana security interface
* Detected brute-force logins, suspicious network scans, and privilege escalations

### 📊 Dashboards

* Created visualizations and dashboards for endpoint logs
* Mapped alerts to the MITRE ATT\&CK framework for context

---

## 🔍 Tools Used

* **Kibana (SIEM & Dashboards)**
* **Nmap**
* **Metasploit Framework**
* **Wireshark**
* **Elastic Agent & Fleet Management**
* **PowerShell Scripting**
* **MITRE ATT\&CK Framework**

---

## 📘 What I Learned

* How to simulate and detect real-world attacks in a safe lab environment
* Fundamentals of log ingestion, parsing, and threat detection
* Practical use of SIEM tools for building detections and visualizing data
* Using offensive tools (like Nmap & Metasploit) to strengthen defensive skills

---

## 📂 Repository Contents

* `/scripts`: Brute-force PowerShell script
* `/dashboards`: JSON exports of Kibana dashboards
* `/rules`: Detection rule configurations
* `/screenshots`: Evidence of alerts, dashboards, and attack simulations

---

## 📫 Contact

If you're a recruiter or engineer interested in this project, feel free to reach out:

* **LinkedIn**: \[https://www.linkedin.com/in/faruq-sowemimo/]
* **Email**: \[Olafaruq1@gmail.com]

---

> "Blue teams don’t just defend; they learn the offense to outthink the attacker."
