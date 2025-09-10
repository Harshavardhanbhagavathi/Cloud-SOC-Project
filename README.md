# Cloud-SOC-Project
“Cloud-based SOC Lab: Brute Force Attack Detection using Microsoft Sentinel (Azure)”
# Cloud SOC Lab – Brute Force Attack Detection

This project demonstrates how brute force attacks against a Windows VM in Azure can be detected using Microsoft Sentinel.

## 🔹 Project Overview
- Built a cloud-based SOC lab on Azure.
- Simulated RDP brute-force attack using Hydra from Kali Linux.
- Collected Windows Security Events (4625, 4624) in Log Analytics.
- Created KQL queries and Sentinel Analytic Rules to detect brute-force.
- Verified Sentinel raised Incidents for attack activity.

## 🔹 Project Reports
- [Day 1 – Azure Setup & First Attack](Day1.md)
- [Day 2 – Brute Force Attack Detection](Day2.md)

## 🔹 Screenshots
![Hydra Output](images/hydra.png)
![Sentinel Query](images/query.png)
![Sentinel Incident](images/incident.png)

## 🔹 Skills Learned
- Microsoft Azure (VMs, Networking)
- Microsoft Sentinel (SIEM)
- KQL (Kusto Query Language)
- Offensive Security (Hydra, Nmap)
- SOC Analyst Workflow (Detect → Investigate → Respond)
