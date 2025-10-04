# Portfolio & Projects (Details)

This repository showcases selected professional projects, labs, and security solutions I have designed and delivered.  
It highlights expertise in penetration testing, offensive security training, compliance solutions, and enterprise-grade simulation environments.  

---

### Table of Contents
- Offensive Security Training Programs
  -  [Certified Penetration Testing Professional (CPTP)](#certified-penetration-testing-professional-cptp)
  -  [Certified Web Application Security Professional (CWASP)](#certified-web-application-security-professional-cwasp)
- [Enterprise Compliance & Monitoring Platform (Essential Eight)](#enterprise-compliance--monitoring-platform-essential-eight)
- [Cybersecurity Labs & Simulation Environments](#cybersecurity-labs--simulation-environments)


## Offensive Security Training Programs

### Certified Penetration Testing Professional (CPTP)

Designed and delivered the Certified Penetration Testing Professional (CPTP) course, a 20-module commercial certification with hands-on labs, officially licensed by NCSC, CREST, and MPG International, and now offered by Tranchulas. [Learn more](https://tranchulas.com/course/hands-on-penetration-testing-and-ethical-hacking-training-course/).

> View the course outline [here](https://tranchulas.com/wp-content/uploads/2025/06/Tranchulas_Penetration_Testing_Ethical_Hacking_Training_Outline.pdf).

![CPTP Information](/media/cptp.png)

![CPTP Course Accreditations](/media/cptp-accreditations.png)

### Certified Web Application Security Professional (CWASP)

Designed and delivered the Certified Web Application Security Professional (CWASP) course, a 21-module commercial certification with hands-on labs, officially licensed by NCSC, CREST, and MPG International, and now offered by Tranchulas. [Learn more](https://tranchulas.com/course/advanced-web-application-penetration-testing-security-training/)

> View the course outline [here](https://tranchulas.com/wp-content/uploads/2025/03/Web-Application-Penetration-Testing-course.pdf).  

![alt text](/media/cwasp.png)
![CPTP Course Accreditations](/media/cptp-accreditations.png)

## Enterprise Compliance & Monitoring Platform (Essential Eight)

Designed and developed a full-scale Essential Eight compliance platform that can be deployed in enterprise environments to monitor and detect systems failing critical security controls.

The software is actively used across organizations to continuously monitor employee systems against the **Essential Eight** compliance framework.  
Administrators have full centralized control via the dashboard, removing the need to manually access individual machines.

**Key Features:**
- Continuous compliance checks for all employee systems.  
- Centralized **admin dashboard** for system-wide control.  
- Add, remove, block, or manage agents remotely.  
- Generate compliance and security reports on demand.  
- Enforce policies without physically accessing user endpoints.  
- Built with secure coding practices, fully updated, and hardened against modern threats.  

> **Note:** Unfortunately, I cannot share many screenshots. The ones shown below are from the development environment, and finalized production screenshots cannot be provided due to confidentiality.  

![Front-end Dashboard](/media/dashboard.png)

![Automatic Report Generation](/media/auto-report-generation.png)

## Cybersecurity Labs & Simulation Environments

### Proxmox-Based Virtual Lab Environment</b>  ![Proxmox](https://img.shields.io/badge/Proxmox-333333?style=plastic&logo=proxmox&logoColor=E57000)  
Architected and maintained a Proxmox-powered enterprise lab consisting of 30+ virtual machines across segmented networks, with snapshotting and attack-path orchestration for red-teaming and malware analysis. Secure remote access is provided via a custom [OpenVPN](https://medium.com/@bericontraster/step-by-step-guide-setting-up-and-troubleshooting-openvpn-on-ubuntu-24-04-513b2341934e) gateway.  

### Custom Vulnerable Lab Development 
  - Designed and deployed multiple purpose-built vulnerable applications and services to support hands-on training and realistic assessments, including:  
    - Web app exploitation (XSS, SQLi, SSTI, IDOR)  
    - Active Directory attacks (Kerberoasting, ACL abuse, lateral movement)  
    - Linux & Windows privilege escalation techniques  
    - SSRF and GraphQL exploitation scenarios  
  - All labs are mapped to real-world attacker methodologies and integrated into classroom and practical exercises for CPTP and CWASP.