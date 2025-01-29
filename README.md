# Enterprise Network Penetration Testing (Capture the Flag)  

## Course: Ethical Hacking (EN2720) – KTH Royal Institute of Technology  
**Duration:** Aug 2023 – Oct 2023  
**Objective:**  
This project involved **penetration testing on a simulated corporate network** in a controlled lab environment. The goal was to **identify vulnerabilities, exploit them, escalate privileges, and capture security flags**, mimicking real-world cybersecurity attacks.

---
## 🔍 Attack Methodology  

### **1. Reconnaissance & Enumeration**  
**Scanned the network using Nmap** to identify live hosts, services, and open ports.  
**Performed web crawling** to find hidden directories and vulnerabilities.  
**Analyzed traffic using Wireshark** to identify unencrypted credentials.  

### **2️. Exploitation**  
**SQL Injection (SQLMap) to dump database credentials.**  
**Brute-forced SSH & FTP logins using Hydra.**  
**Exploited Apache Tomcat’s misconfigured manager console to deploy a reverse shell.**  

### **33. Privilege Escalation**  
**Kernel exploits** to escalate privileges on a misconfigured Linux server.  
**Used Mimikatz to dump Windows credentials and escalate privileges.**  

### **4️. Post-Exploitation & Lateral Movement**  
**Maintained access by deploying persistent backdoors.**  
**Pivoted to other systems using compromised credentials.**  
**Captured high-value security flags from database servers.**   


### **5️. WiFi & Cloud Security Assessments**
**Traffic Sniffing (Wireshark)** – Captured and analyzed packets to detect **unencrypted credentials & ARP spoofing attacks**.  
**WiFi Cracking (Aircrack-ng)** – Captured WPA2 handshakes and attempted **brute-force key recovery attacks**.  
**Cloud Exploitation** – Identified **misconfigured cloud storage & IAM policy vulnerabilities** for privilege escalation.  


---

## Tools & Techniques Used  
- **Reconnaissance:** Nmap, Wireshark, Burp Suite  
- **Exploitation:** SQLMap, Metasploit, Hydra  
- **Privilege Escalation:** Mimikatz, Linux Exploit Suggester  
- **Post-Exploitation:** Netcat, reverse shells, PowerShell  
- **WiFi & Cloud Attacks:** Aircrack-ng, FoxyProxy  

---

## Key Learnings & Takeaways  
✔ **Developed hands-on penetration testing skills** aligned with real-world cybersecurity challenges.  
✔ **Gained deep insights into attack methodologies**, including **privilege escalation and lateral movement**.  
✔ **Understood vulnerability exploitation** affecting **web apps, servers, and networks**.  
✔ **Learned blue team defense techniques** to mitigate cyber threats.  

---

## Repository Notes  
**The full attack methodologies, logs, and detailed notes are stored in the private document (protected as per KTH course guidelines).**  
**This repository serves as a high-level documentation of the project, showcasing ethical hacking skills and real-world cybersecurity techniques.**  

---
**Feel free to explore this project and reach out for discussions on cybersecurity and penetration testing!**  
