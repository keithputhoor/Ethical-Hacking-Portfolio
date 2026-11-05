# Network Scanning & Service Enumeration (Nmap & UFW)

**Domain:** Ethical Hacking

## Overview & Methodology
Evaluates host discovery, port scanning, service fingerprinting, and firewall rule probing using **Nmap** against an isolated target VM before and after enabling **UFW (Uncomplicated Firewall)**:
1. **Host Discovery & OS/Service Fingerprinting:** Executed ICMP ping sweeps (`nmap -sn`), TCP SYN stealth scans (`nmap -sS`), OS fingerprinting (`nmap -O`), and service/version detection (`nmap -sV`, `nmap -A -p 21`).
2. **Firewall Hardening & Stateful Rule Verification:** Enabled `ufw` on the target host, selectively permitted specific ports, and compared `SYN` (`-sS`), `ACK` (`-sA`), and `Xmas` (`-sX`) scan responses with polite timing templates (`-T2`) to distinguish filtered vs. unfiltered states.

## Technical Evidence & Screenshots

![image1](assets/image1.png)

![image10](assets/image10.png)

![image11](assets/image11.png)

![image12](assets/image12.png)

![image13](assets/image13.png)

![image14](assets/image14.png)

![image15](assets/image15.png)

![image16](assets/image16.png)

![image17](assets/image17.png)

![image18](assets/image18.png)

![image19](assets/image19.png)

![image2](assets/image2.png)

![image20](assets/image20.png)

![image3](assets/image3.png)

![image4](assets/image4.png)

![image5](assets/image5.png)

![image6](assets/image6.png)

![image7](assets/image7.png)

![image8](assets/image8.png)

![image9](assets/image9.png)
