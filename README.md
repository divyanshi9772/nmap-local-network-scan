# Nmap Local Network Port Scan 🔍

## 🧪 Objective:
To perform a basic reconnaissance scan using Nmap to identify devices and open ports on my local network.

## 🛠️ Tools Used:
- Nmap (https://nmap.org/)
- Command Prompt (Windows)

## 🧾 Steps Performed:
1. Found my local IP and subnet mask using `ipconfig`
2. Determined the IP range: `192.168.29.0/24`
3. Ran a TCP SYN scan: `nmap -sS 192.168.29.0/24`
4. Identified active devices and their open ports
5. Analyzed services running on those ports
6. Disabled or blocked risky ports via Windows Firewall

## 📊 Key Findings:
- PC had risky ports: 135, 139, 445, 1521, 8080, 903
- Router had exposed ports: 80, 443, 8080, 8443, 8200, etc.
- Smart/mobile devices had minimal exposure

## 🔐 Actions Taken:
- Disabled file and printer sharing
- Blocked high-risk ports
- Re-scanned and verified closure

## 📁 Files Included:
- `scan_results.txt`: Nmap raw output
- `report.md`: Explanation of results and actions
- `README.md`: Overview of the project

## ✅ Outcome:
Gained skills in network scanning, analysis, and basic security hardening.
