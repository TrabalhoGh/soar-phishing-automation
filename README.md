# My First SOAR - Phishing Analysis Automation 🛡️

## Overview
This project demonstrates an automated workflow created in **Tines** to streamline the analysis of suspicious emails (Phishing). The goal is to reduce response time (MTTR) by automatically extracting and analyzing Indicators of Compromise (IOCs).

## 🚀 Features
* **Automated Extraction:** Automatically pulls URLs and attachments from incoming emails.
* **Threat Intelligence Integration:** Connects with external APIs (like VirusTotal) to check for malicious reputations.
* **Decision Logic:** Categorizes emails based on the threat level detected.
* **Alerting:** Notifies security analysts only when a high-risk threat is confirmed.

## 🛠️ Tools & Technologies
* **SOAR Platform:** Tines
* **Format:** JSON / REST API
* **Security Concepts:** Incident Response, Phishing Triage, IOC Analysis.

## 📈 Architecture Diagram
<img width="924" height="412" alt="MyfirstSOAR" src="https://github.com/user-attachments/assets/fbe9ee4c-ad99-4836-bd36-78673f9f8d80" />

## 📖 How to Use
1. Download the `my-first-soar.json` file from this repository.
2. Log into your **Tines** tenant.
3. Click on **Import** and select the JSON file.
4. (Optional) Configure your own API credentials (e.g., VirusTotal, Outlook/Gmail) in the Tines "Credentials" section to make it fully functional.

---
*Created as part of my Cybersecurity specialization and preparation for CompTIA Security+.*
