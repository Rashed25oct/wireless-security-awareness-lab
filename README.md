# Wireless Security Awareness and Rogue Access Point Detection Lab

## Overview
This project demonstrates a complete cybersecurity workflow including network reconnaissance, web-based security awareness, traffic analysis, and defensive techniques using Kali Linux.

## Tools Used
- Kali Linux
- Nmap
- Wireshark
- Flask (Python)
- iptables

## Project Phases

### — Network Reconnaissance
- Identified network configuration
- Performed host discovery using Nmap
- Conducted service scanning

### — Flask Awareness Application
- Built a web-based security awareness portal
- Simulated risks of public Wi-Fi networks
- Implemented user interaction flow

### — Network Traffic Analysis
- Captured live traffic using Wireshark
- Analyzed DNS, DHCP, and TCP protocols
- Observed encrypted traffic behavior

###  — Detection & Defense
- Detected TCP Reset (RST) packets
- Simulated blocked connections
- Analyzed firewall rules (iptables)
- Monitored DNS queries for suspicious domains


---

## Screenshots

### Network Reconnaissance
![Network Info](screenshots/01_network_info.png)  
![Kali Environment](screenshots/02_kali_environment.png)  
![Nmap Host Scan](screenshots/03_nmap_host_scan.png)  
![Nmap Service Scan](screenshots/04_nmap_service_scan.png)  

---

### Flask Awareness Portal
![Flask Home](screenshots/05_flask_home_page.png)  
![Security Reminder](screenshots/06_flask_security_reminder.png)  
![Flask Running](screenshots/07_flask_running_terminal.png)  

---

### Traffic Analysis (Wireshark)
![Live Capture](screenshots/08_wireshark_live_capture.png)  
![DNS Filter](screenshots/09_dns_filter.png)  
![DHCP Filter](screenshots/10_dhcp_filter.png)  
![TCP Traffic](screenshots/11_tcp_traffic.png)  
![Capture Stopped](screenshots/12_capture_stopped.png)  

---

### Detection & Defense
![TCP RST Detection](screenshots/13_tcp_rst_detection.png)  
![DNS Specific Filter](screenshots/14_dns_specific_filter.png)  
![DNS Google Filter](screenshots/15_dns_google_filter.png)  
![Firewall Rules](screenshots/16_firewall_rules.png)  

---


## 📄 Report
Full detailed report available in:
`Final_Wireless_Security_Report.pdf`

---


## Key Learning Outcomes
- Network reconnaissance using Nmap
- Web application development with Flask
- Network traffic analysis using Wireshark
- Detection of abnormal network behavior
- Basic firewall configuration and analysis

  ## ⚠️ Disclaimer
This project is for educational purposes only. All testing was performed in a controlled lab environment.

## Author
Rashed Rahman  
MS in Cybersecurity  
Houston Christian University
