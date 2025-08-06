# 🔍 Task 1 – Network Port Scanning | Cybersecurity Internship

This project demonstrates basic network reconnaissance using **Nmap**, focusing on identifying open ports in a private network. It was completed as part of the Elevate Labs Cybersecurity Internship.

---

** Tools Used**
- **Nmap** – For port scanning (`-sS` TCP SYN scan)
- **Wireshark** – For packet analysis

---

## Objectives
- Learn how to identify devices on a local network
- Discover open ports and understand their associated services
- Assess potential risks associated with exposed ports

---

##  Steps Performed
1. Identified local IP range using `ip a`  
   → Example: `192.168.x.x/24`
2. Ran a TCP SYN scan using:
   ```bash
   nmap -sS 192.168.x.x/24
   
**
   ##  Screenshot**

![Nmap Scan Output](nmap_scan.png)

