# Ethical Hacking Portfolio

![Domain](https://img.shields.io/badge/Domain-Ethical_Hacking-d32f2f?style=flat-square)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-Offensive_Security-557c94?style=flat-square)
![Nessus](https://img.shields.io/badge/Tenable-Nessus-00b388?style=flat-square)
![Metasploit](https://img.shields.io/badge/Metasploit-Framework-2596be?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-Web_Pentesting-ff6633?style=flat-square)

Penetration testing reports, enterprise vulnerability remediation scripts, packet captures, and offensive security lab write-ups completed for **Ethical Hacking**.

---

## Flagship Assessments & Remediation Projects

| Project | Stack & Tools | Summary | Directory |
| :--- | :--- | :--- | :--- |
| **Enterprise Vulnerability Assessment & Remediation Simulation** | Tenable Nessus, Wireshark, Metasploit, Redis, Ruby Rack, ISO/IEC 27001 | Credentialed vs. unauthenticated subnet vulnerability scanning, CVSS v3 prioritization, Wireshark cleartext verification, and hardening configurations for Redis (CVSS 9.8) & Ruby Rack. | [`enterprise-vulnerability-remediation/`](./enterprise-vulnerability-remediation/) |
| **OWASP Juice Shop Web Application Penetration Test** | Burp Suite, Kali Linux, Node.js/Express, OWASP Top 10 (2021) | Passive spidering, REST API parameter enumeration (`/rest/user/login`, `/rest/products/search`), and vulnerability mapping across SQLi (A03), Reflected XSS (A03), and Broken Access Control (A01). | [`project-owasp-juiceshop-pentest/`](./project-owasp-juiceshop-pentest/) |

---

## Ethical Hacking — Lab Portfolio

All offensive security labs are documented under [`labs/`](./labs/) with command walk-throughs and extracted terminal/Wireshark screenshots:

| Lab | Topic | Key Tools & Techniques | Directory |
| :--- | :--- | :--- | :--- |
| **Lab 02** | Intelligence Gathering & Reconnaissance | `whois`, `dig`, `nslookup`, `traceroute`, DNS Authoritative & MX Enumeration | [`labs/Lab-02-Reconnaissance-and-Footprinting/`](./labs/Lab-02-Reconnaissance-and-Footprinting/) |
| **Lab 03** | Network Packet Capture & TLS Decryption | Wireshark, `SSLKEYLOGFILE` (`sslkeys.log`), TCP 3-Way & TLS Handshake Inspection, PCAP Analysis | [`labs/Lab-03-Wireshark-Packet-Capture-and-TLS-Decryption/`](./labs/Lab-03-Wireshark-Packet-Capture-and-TLS-Decryption/) |
| **Lab 04** | Network Scanning & Service Enumeration | `nmap` (`-sS`, `-sV`, `-O`, `-A`, `-sA`, `-sX`, `-T2`), UFW Firewall Filtering Verification | [`labs/Lab-04-Network-Scanning-and-Enumeration-Nmap/`](./labs/Lab-04-Network-Scanning-and-Enumeration-Nmap/) |
| **Lab 05** | ARP Spoofing & Man-in-the-Middle (MITM) | `arpspoof`, IP Forwarding, ARP Cache Poisoning Verification, MITM Packet Capture | [`labs/Lab-05-ARP-Spoofing-and-MITM-Attacks/`](./labs/Lab-05-ARP-Spoofing-and-MITM-Attacks/) |
| **Lab 06** | Password Auditing & Credential Sniffing | Rainbow Tables (`rtgen`, `rcrack`), John the Ripper, THC-Hydra, Burp Suite Auth Intercept | [`labs/Lab-06-Password-Cracking-RainbowTables-John-Hydra/`](./labs/Lab-06-Password-Cracking-RainbowTables-John-Hydra/) |
| **Lab 07** | System Vulnerability Exploitation | Metasploit Framework (`msfconsole`), Payload Delivery, Remote Shell Escalation | [`labs/Lab-07-System-Exploitation-Metasploit/`](./labs/Lab-07-System-Exploitation-Metasploit/) |
| **Lab 08** | Web Application Exploitation (SQLi & RFI) | Remote File Inclusion (RFI), SQL Injection Auth Bypass (`' OR 1=1 #`), Session Hijacking | [`labs/Lab-08-Web-Exploitation-SQLi-RFI/`](./labs/Lab-08-Web-Exploitation-SQLi-RFI/) |
| **Lab 09** | Windows Exploitation via Crafted Executables | AutoIt / Crafted Decoy Executables (`calc.exe` decoy + remote payload staging) | [`labs/Lab-09-Windows-Exploitation-Crafted-Payloads/`](./labs/Lab-09-Windows-Exploitation-Crafted-Payloads/) |
| **Lab 10** | Wireless WPA/WPA2 Password Auditing | WPA2 4-Way Handshake Capture, Deauthentication Attack, Dictionary Auditing Simulator | [`labs/Lab-10-Wireless-WPA2-Password-Auditing/`](./labs/Lab-10-Wireless-WPA2-Password-Auditing/) |
