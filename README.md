> This document presents an overview of cybersecurity material I have mastered throughout my learning path (covering both theory and practice), as well as my earned certifications.

# I. Certificates:

## 1. GIAC Certified Incident Handler (GCIH) 

(ACCREDITATION: https://www.credly.com/badges/0493d5d4-cdad-49c1-aed6-df246b1f0e68)

## 2. GIAC Security Essentials Certification (GSEC)
(ACCREDITATION: https://www.credly.com/badges/cc11769e-90a2-431f-ae58-971abe665e64)

## 3. GIAC Foundational Cybersecurity Technologies (GFACT)
(ACCREDITATION: https://www.credly.com/badges/a9e3829a-b90d-415c-8dcf-43b9fb15086d)

# II. Courses:

## 1. SEC504: Hacker Tools, Techniques, and Incident Handling (SANS Institute)
   > During the course I learnt the following concepts and practised the usage of the following tools:
   - Incident Response and Cyber Investigations (Live Windows Investigation; Network, Memory and  Malware Investigations) \
     <ins>Tools</ins>: PowerShell, Tcpdump, Volatility, Regshot, Procmon
   - Scanning and Enumeration Attacks (MITRE ATT&CK Framework; Network, Host, and Cloud Scanning; SMB Security; Windows Logging; Data Exfiltration) \
     <ins>Tools</ins>: Nmap, Netcat, Masscan, SMBclient, RPCclient, SMBeagle, PowerShell, Hayabusa
   - Password Attacks and Exploit Frameworks (Types of Password Attacks, Micrisift 365 Attaks, Hashing, Password Cracking, Metasploit Framework, Drive-By Attacks) \
     <ins>Tools</ins>: Hydra, Nmap, CeWL, MSOLSpray, Hashcat, Netcat
   - Web Application Attacks (IDOR, Command Injection, XSS, SQL Injection, SSRF and IMDS Attacks, Insecure Storage) \
     <ins>Tools</ins>: Metasploit, Hayabusa, Sqlmap, curl
   - Evasion and Post-Exploitation Attacks (Endpoint Security Bypass, Pivoting and Lateral Movement, Hijacking, Persistenc, Threat Analysis, Cloud Post_exploitation) \
     <ins>Tools</ins>: PowerShell, Metasploit, Responder, RITA, ScoutSuite, Zeek, CloudMapper



## 2. SEC401: Security Essentials - Network, Endpoint, and Cloud (SANS Institute)
   > During the course I learnt the following concepts and practised the usage of the following tools:
   - Network Security and Cloud Essentials (Sniffing, Packet Analysis, Securing Wireless Networks) \
     <ins>Tools</ins>: Tcpdump, Wireshark
   - Defense in Depth (Zero Trust, Password Auditing, IAM, DLP) \
     <ins>Tools</ins>: John the Ripper, Hashcat, Exiftool 
   - Vulnerability Management and Response (Vulnerability Assesment, Penetration Testing, Malware Analysis, Log Management, DFIR) \
     <ins>Tools</ins>: Nmap, Metasploit, PowerShell, ElasticStack SIEM
   - Data Security Technologies \
     <ins>Tools</ins>: Nmap, GPG, Snort, Zeek
   - Windows and Azure Security \
     <ins>Tools</ins>: PowerShell, System Informer, Sysinternals, gpdedit.msc, Event Viewer 
   - Containers, Linux, and Mac Security \
     <ins>Tools</ins>: Docker, Auditd, Sysmon
     
## 3. SEC275: Foundations: Computers, Technology, & Security (SANS Institute)
> During the course I learnt the fundamentals of: Linux, Web, Networking, Servers and Services, Windows, Computer Hardware. \
> I also learned the basics of the following languages: C, Python, Assembly, SQL.

# III. Platforms:

## 1. Hack the Box: 
A) Academy (modules):
- Web Requests (BADGE: https://academy.hackthebox.com/achievement/badge/1798031e-02c5-11ee-acfc-bea50ffe6cb4)
- Intro to Assembly Language (BADGE: https://academy.hackthebox.com/achievement/badge/ef579c3f-e6b4-11ee-b18d-bea50ffe6cb4)
- Attacking Common Services (IN PROGRESS)

B) Labs (machines):
- Meow (Very Easy)
- Fawn (Very Easy)
- Dancing (Very Easy)
- Redemeer (Very Easy)
- Appointment (Very Easy)
- Sequel (Very Easy)
- Crocodile (Very Easy)
- Responder (Very Easy)
- Three (Very Easy)

## 2. Try Hack Me (modules):
- What is Networking?
- 

## 3. Blue Team Labs: 
A) Investigations:
- Deep Blue (Easy)
> I conducted Windows log analysis in search of a host compromised throud RDP protocol. \
<ins>Tools</ins>: DeepBlueCLI, PowerShell, Event Viewer \
BADGE: https://blueteamlabs.online/achievement/share/92426/32

- Piggy (Easy)
> I investigated network activity from .pcap files. \
<ins>Tools</ins>: Wireshark, OSINT, MITRE ATT@CK Framework \
BADGE: https://blueteamlabs.online/achievement/share/92426/66

B) Challenges:
- Source (Medium)
> I reviewed code to identify a vulnerability.
- Browser Forensics - Cryptominer (Easy)
> I inspected an .ad1 file in search of a cryptominer. \
<ins>Tools</ins>: FTK Imager
- Secrets (Easy)
>  I learnt how to inspect a JSON Web Token. \
<ins>Tools</ins>: jwt.io/#debugger, Hashcat
- Network Analysis - Webshell (Easy)
>  I inspected a .pcap file in search of a suspicious activity. \
<ins>Tools</ins>: Wireshark
- Phishing Analysis 1 (Easy)
> I practised finding essential information from an e-mail such as the original sender, the originating IP and scanned information from the attachment. \
- Phishing Analysis 2 (Easy)
> I practised finding essential information from an e-mail such as the company is the attacker trying to imitate, the URL of the main call-to-action button and inppecting the URL information without opening it. \
<ins>Tools</ins>: Mozilla Thunderbird, CyberChef, browserling.com
- ATT&CK (Easy)
> I practiced working with ATT&CK framework. \
<ins>Tools</ins>: MITRE ATT&CK framework
- The Report (Easy)
> I practiced working with a Security Report.

## 4. Let's Defend:

## 5. Open Security Training:
- Architecture 1001: x86-64 Assembly (IN PROGRESS)

## 5. PortSwigger Academy (labs):
- SQL injection

# IV. Webinars and online trainings:
## 1. Sekurak Academy:
- Introduction to low level hacking: Operating on bits and bytes - Gynvael Coldwind (2023)
- Hacking vs AI - Tomasz Turba (2023)
- Can anything be hacked with Python? - Mateusz Lewczak (2023)
- PowerShell in Security: fundamentals, tricks and practice - Paweł Maziarz (2023)
- Introduction to Linux Security, Part I - Karol Szafrański (2024)
- Computer Forensics in Linux - Tomasz Turba (2024)
- Introduction to IoT Security (4 parts) - Mateusz Wójcik (2024)
  

## 2. O'Reilly:
- IPv4 Subnetting from Beginning to Mastery \
  BADGE: https://www.credly.com/badges/b1dc3bb1-2335-4fae-98bb-a437be6a0820/public_url
> During the training I learnt the concept of IPv4 subnetting. I am capable of understanding  understanding the IPv4 concepts and mathematical processes involved,
and applying them effectively in designing, engineering, and operating TCP/IP networks. I am also prepared to quickly perform subnetting calculations without a calculator.

- Packet Analysis Using Wireshark \
  BADGE: https://www.credly.com/badges/0f8338c3-01a6-48d4-98d7-1d26c3f30f32/public_url
> I learnt how to analyze network traffic using Wireshark, including reconstructing conversations, extracting pictures and credentials, and analyzing maltraffic.

- TCP/IP Fundamentals \
  BADGE: https://www.credly.com/badges/3ed2ff68-e7a1-44dc-b734-6123711413a4/public_url
> I learnt the foundational concepts of TCP/IP protocols and their practical usage in modern enterprise and cloud provider networking. 
I am equipped with the knowledge to use TCP/IP protocols in LANs, WANs, and on the global Internet, including with cloud providers like AWS, GCP, and Microsoft Azure.

- Linux Fundamentals Bootcamp \
  BADGE: https://www.credly.com/badges/bb1402c4-2a05-42bb-baea-e3bbd4baeddd/public_url
> I am capable of understanding and using Linux quickly, with the skills needed to start a career in security, systems administration, and cloud engineering. 
I also have a solid foundation for Linux certifications like LFCS, LPIC-1, and Linux+.

- Build Your Own Cybersecurity Lab and Cyber Range \
  BADGE: https://www.credly.com/badges/5f950f5d-e2a6-4910-941d-ae2f64f281d7/public_url

# V Programming Languages:
## 1. Python:
   I am capable of writing simple scrips in Python. \
   I practice Python scripting from various sources, the source is always given in the comments section of a script. \
   Exercises Repository: https://github.com/Agnieszka000/Python_exercises 
   Cybersecurity Scripts Repository: https://github.com/Agnieszka000/Cybersecurity-scripts


## 2. JavaScript:
- I learnt JavaScript basics during the challenge Summer of Code. (REPOSITORY: https://github.com/Agnieszka000/summer_of_code)

# VI. CTFs:

# VII. Books:
- Learn Computer Forensics by William Oettinger (IN PROGRESS)

# VIII. Challenges:
- Summer of Code: (REPOSITORY: https://github.com/Agnieszka000/summer_of_code)
> During this 8-week-challenge I mastered the basics of HTML, Css, JavaScript and Python as used in the web environment.
I also familiarized myself with the concepts of web scraping and information extraction through API.

