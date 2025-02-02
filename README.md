# CYBERSECURITY LEARNING PATH

> This document presents an overview of cybersecurity material I have mastered throughout my learning path (covering both theory and practice), as well as my earned certifications.
> The sections:
> - [Certificates] (#certificates:)
> - [II. Courses] (# II. Courses:)
> - III. Platforms
> - IV. Webinars and online trainings
> - V. Programming Languages
> - VI. CTFs
> - VII. Books
> - VIII. Challenges

# Certificates:

## 1. GIAC Certified Incident Handler (GCIH) 
Credly: https://www.credly.com/badges/0493d5d4-cdad-49c1-aed6-df246b1f0e68

## 2. GIAC Security Essentials Certification (GSEC)
Credly: https://www.credly.com/badges/cc11769e-90a2-431f-ae58-971abe665e64

## 3. GIAC Foundational Cybersecurity Technologies (GFACT)
Credly: https://www.credly.com/badges/a9e3829a-b90d-415c-8dcf-43b9fb15086d

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

## 4. Windows Forensics with Belkasoft (IN PROGRESS)

# III. Platforms:

## 1. Hack the Box: 
A) Academy (modules):
- Web Requests \
  Badge: https://academy.hackthebox.com/achievement/badge/1798031e-02c5-11ee-acfc-bea50ffe6cb4)
- Intro to Assembly Language \
  Badge: https://academy.hackthebox.com/achievement/badge/ef579c3f-e6b4-11ee-b18d-bea50ffe6cb4)
- Attacking Common Services (IN PROGRESS)

B) Labs (machines):
- Archetype - Tier 2 - SMB; Tools: SMBclient, Impacket, PowerShell
- Appointment - Tier 1 - SQL database
- Sequel - Tier 1 - MySQL
- Crocodile - Tier 1 - ftp protocol
- Responder - Tier 1 - Wappalyzer plug-in
- Three - Tier 1 - AWS cloud
- Meow - Tier 0 - telnet protocol
- Fawn - Tier 0 - ftp protocol
- Dancing - Tier 0 - SMB & the usage of SMBclient
- Redemeer - Tier 0 - Redis database


## 2. Microsoft Learn:
A) Azure Sentinel Training Lab
> I deployed a Microsoft Sentinel workspace and worked on: installing and enabling data connectors, creating rules for security detections through Analytics Rules, handling an incident through working with logs, playbooks and workbooks, creating watchlists, working with threat intelligence connectors.

B) Modules:
- Introduction to Microsoft Sentinel \
  Badge: https://learn.microsoft.com/api/achievements/share/en-us/Agnieszka-6671/VD9WXQFM?sharingId=E4EE8BF3E3FBD180
- Create and manage Microsoft Sentinel workspaces\
  Badge: https://learn.microsoft.com/api/achievements/share/en-us/Agnieszka-6671/UYEJEEW3?sharingId=E4EE8BF3E3FBD180
- Query logs in Microsoft Sentinel \
  Badge: https://learn.microsoft.com/api/achievements/share/en-us/Agnieszka-6671/WZDJUBYN?sharingId=E4EE8BF3E3FBD180
- Use watchlists in Microsoft Sentinel \
  Badge: https://learn.microsoft.com/api/achievements/share/en-us/Agnieszka-6671/UYP4U9C3?sharingId=E4EE8BF3E3FBD180
- Utilize threat intelligence in Microsoft Sentinel \
  Badge: https://learn.microsoft.com/api/achievements/share/en-us/Agnieszka-6671/2BUHL6CV?sharingId=E4EE8BF3E3FBD180
- Mitigate incidents using Microsoft Defender \
  Badge: https://learn.microsoft.com/api/achievements/share/en-us/Agnieszka-6671/P58SQSZ4?sharingId=E4EE8BF3E3FBD180
- Write your first query with Kusto Query Language \
  Badge: https://learn.microsoft.com/api/achievements/share/en-us/Agnieszka-6671/UYE7A673?sharingId=E4EE8BF3E3FBD180
- Introduction to Microsoft Defender XDR threat protection \
  Badge: https://learn.microsoft.com/api/achievements/share/en-us/Agnieszka-6671/UYQT8RY3?sharingId=E4EE8BF3E3FBD180


## 3. Blue Team Labs: 
A) Investigations:
- Swift
> I collected key artifacts for analysis and triage after a Windows system compromise. I reviewed the Lockout Policy,
> investigated Windows Logs, used WHOIS tools, identified compromised accounts and malicious scripts, and investigated data exfiltration. \
<ins>Tools</ins> PowerShell, Live Forensicator (PowerShell framework), Chainsaw \
Badge: https://blueteamlabs.online/achievement/share/92426/114

- Deep Blue
> I conducted Windows log analysis in search of a host compromised through RDP protocol. \
<ins>Tools</ins>: DeepBlueCLI, PowerShell, Event Viewer \
Badge: https://blueteamlabs.online/achievement/share/92426/32

- Piggy
> I investigated network activity from .pcap files. \
<ins>Tools</ins>: Wireshark, OSINT, MITRE ATT@CK Framework \
Badge: https://blueteamlabs.online/achievement/share/92426/66

B) Challenges:
- Log Analysis - Sysmon
> I analyzed a Sysmon log file from a compromised Windows host, using Linux CLI and CyberChef.
Badge: https://blueteamlabs.online/achievement/share/challenge/92426/18
- Source
> I reviewed code to identify a vulnerability.
- Browser Forensics - Cryptominer
> I inspected an .ad1 file in search of a cryptominer. \
<ins>Tools</ins>: FTK Imager \
Badge: https://blueteamlabs.online/achievement/share/challenge/92426/38
- Secrets
>  I learnt how to inspect a JSON Web Token. \
<ins>Tools</ins>: jwt.io/#debugger, Hashcat \
Badge: https://blueteamlabs.online/achievement/share/challenge/92426/35
- Network Analysis - Webshell
>  I inspected a .pcap file in search of a suspicious activity. \
<ins>Tools</ins>: Wireshark \
Badge: https://blueteamlabs.online/achievement/share/challenge/92426/12
- Phishing Analysis 1
> I practised finding essential information from an e-mail such as the original sender, the originating IP and scanned information from the attachment. \
Badge: https://blueteamlabs.online/achievement/share/challenge/92426/16
- Phishing Analysis 2
> I practised finding essential information from an e-mail such as the company is the attacker trying to imitate, the URL of the main call-to-action button and inspecting the URL information without opening it. \
<ins>Tools</ins>: Mozilla Thunderbird, CyberChef, browserling.com \
Badge: https://blueteamlabs.online/achievement/share/challenge/92426/24
- ATT&CK
> I practiced working with ATT&CK framework. \
<ins>Tools</ins>: MITRE ATT&CK framework \
Badge: https://blueteamlabs.online/achievement/share/challenge/92426/15
- The Report
> I practiced working with a Security Report. \
Badge: https://blueteamlabs.online/achievement/share/challenge/92426/42

## 4. Try Hack Me (modules):
- What is Networking?
- Intro to LAN
- Windows Fundamentals
- Linux Fundamentals
- OSI Model
- Packets and Frames
- DNS in Detail
- HTTPS in Detail
- How Websites Work
- NMAP
- SQL Injection
- Google Dorking
- Pentesting Fundamentals
- Subdomain Enumeration
- Authentication Bypass
- IDOR
- Intro to Containerisation
- File Inclusion
- x86 Architecture Overview

## 5. Let's Defend (courses):
- Malware Analysis Fundamentals
- Dynamic Malware Analysis
- Building a Malware Analysis Lab
- Malware Traffic Analysis with Wireshark

## 6. Open Security Training:
- Architecture 1001: x86-64 Assembly (IN PROGRESS)

## 7. PortSwigger Academy (labs):
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
  Badge: https://www.credly.com/badges/b1dc3bb1-2335-4fae-98bb-a437be6a0820/public_url
> During the training I learnt the concept of IPv4 subnetting. I am capable of understanding  understanding the IPv4 concepts and mathematical processes involved,
and applying them effectively in designing, engineering, and operating TCP/IP networks. I am also prepared to quickly perform subnetting calculations without a calculator.

- Packet Analysis Using Wireshark \
  Badge: https://www.credly.com/badges/0f8338c3-01a6-48d4-98d7-1d26c3f30f32/public_url
> I learnt how to analyze network traffic using Wireshark, including reconstructing conversations, extracting pictures and credentials, and analyzing maltraffic.

- TCP/IP Fundamentals \
  Badge: https://www.credly.com/badges/3ed2ff68-e7a1-44dc-b734-6123711413a4/public_url
> I learnt the foundational concepts of TCP/IP protocols and their practical usage in modern enterprise and cloud provider networking. 
I am equipped with the knowledge to use TCP/IP protocols in LANs, WANs, and on the global Internet, including with cloud providers like AWS, GCP, and Microsoft Azure.

- Linux Fundamentals Bootcamp \
  Badge: https://www.credly.com/badges/bb1402c4-2a05-42bb-baea-e3bbd4baeddd/public_url
> I am capable of understanding and using Linux quickly, with the skills needed to start a career in security, systems administration, and cloud engineering. 
I also have a solid foundation for Linux certifications like LFCS, LPIC-1, and Linux+.

- Build Your Own Cybersecurity Lab and Cyber Range \
  Badge: https://www.credly.com/badges/5f950f5d-e2a6-4910-941d-ae2f64f281d7/public_url

# V. Programming Languages:
## 1. Python:
   I am capable of writing simple scrips in Python. \
   I practice Python scripting from various sources, the source is always given in the comments section of a script. \
   Exercises Repository: https://github.com/Agnieszka000/Python_exercises \
   Cybersecurity Scripts Repository: https://github.com/Agnieszka000/Cybersecurity-scripts


## 2. JavaScript:
- I learnt JavaScript basics during the challenge Summer of Code. \
  Repository: https://github.com/Agnieszka000/summer_of_code

# VI. CTFs:
- Cyber Apocalypse 2023 (HTB)
- WiCyS & SANS CTF (2023, WiCyS Security Training Scholarship Tier 1)
- Cyber Apocalypse 2024 (HTB)
- Cyber Defense 2024 (WiCyS)
- Flare-On 11 (2024)
- 4T$ CTF (2024)
- SANS Holiday Hack Challenge (2024)

# VII. Books:
- Learn Computer Forensics by William Oettinger (IN PROGRESS)

# VIII. Challenges:
- Summer of Code: \
  Repository: https://github.com/Agnieszka000/summer_of_code
> During this 8-week-challenge I mastered the basics of HTML, Css, JavaScript and Python as used in the web environment. \
I also familiarized myself with the concepts of web scraping and information extraction through API.

