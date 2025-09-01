# SIEM Log Analysis & Threat Hunting

## 📌 Overview
This project demonstrates how to ingest and analyse logs using a SIEM tool to detect threats and anomalies. The goal is to replicate the work of a SOC analyst by building a dashboard, investigating events, and documenting findings.

## 🛠 Tools Used
- Splunk Free / ELK Stack / Wazuh
- Sample Windows/Linux log files
- Sysmon (for Windows event collection)

## 🔍 Steps
1. Install and configure Splunk (or ELK).
2. Import sample logs (Windows Security, Linux auth, network logs).
3. Create queries to detect:
   - Failed login attempts
   - Brute-force attacks
   - Suspicious processes
4. Build a dashboard with alerts.
5. Document key incidents found.

## 📊 Findings
- [Add screenshots of dashboards and alerts]
- Example: 50 failed login attempts from suspicious IP `192.168.1.20`.

## 📑 Report
- Created an **Incident Response Report** including:
  - Event summary
  - Detection method
  - Recommended mitigation

## 🎯 Skills Learned
- SIEM log ingestion and analysis
- Threat hunting queries
- Incident response reporting
