# 🕵️ Ethical Hacking Lab

## 📌 Overview
This project was conducted as part of a cybersecurity bootcamp to practice **ethical hacking techniques** in a controlled environment.  
The goal was to assess vulnerabilities on a **Production server** and a **Web server in a DMZ**, exploit weaknesses, and provide recommendations for improving security.

⚠️ **Disclaimer:** This project was performed in a **lab environment only**. The tools and exploits should only be used for authorized security testing.

---

## 📂 Project Structure

📂 ethical-hacking-lab

├── scans/ # Nmap scans and results

├── exploits/ # Metasploit scripts and exploitation notes

├── docs/ # Screenshots, reports, presentation slides

└── README.md


---

## 🚀 Tasks Performed
- Installed a **Production server VM** in the Trusted network (VirtualBox).  
- Scanned for vulnerabilities on both the Production server and Web server using **Nmap** (`nmap -sV --script vuln`).  
- Researched CVEs for identified vulnerabilities.  
- Exploited at least **2 vulnerabilities per server** using **Metasploit** (vsftpd, Samba), gaining root access.  
- Created a **backdoor account** on the Production server with root permissions.  
- Explored system files (`/etc/passwd`, `/etc/shadow`) and cracked passwords.  
- Extracted sensitive files (safe combination, recipes, vulnerability lists).  

---

## 🛠️ Tools & Technologies
- **Kali Linux**  
- **Nmap** (vulnerability scanning)  
- **Metasploit** (exploitation)  
- **VirtualBox** (VM environment)  

---

## 📊 Results
- Demonstrated end-to-end penetration testing workflow.  
- Verified critical vulnerabilities (FTP, Samba) and gained **root access**.  
- Identified weak configurations such as default credentials and unnecessary services.  
- Provided **security recommendations**:  
  - Apply software updates and patches  
  - Disable unused services  
  - Harden system configurations  
  - Implement **firewall rules and IDS/IPS**  
  - Restrict account access and enforce least privilege  
