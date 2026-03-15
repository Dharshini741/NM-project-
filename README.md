Design and Apply Context-Aware Access Controls Based on User Identity, Device Posture, Location, and Application Risk
Project Overview

This project focuses on designing a context-aware access control system based on Zero Trust Architecture (ZTA) principles.
Traditional security models rely on perimeter defenses such as VPNs and firewalls, assuming that users inside the network can be trusted. 
However, modern environments involve cloud services, remote work, personal devices, and third-party access, making traditional models insufficient.

This project demonstrates how dynamic access decisions can be made using contextual signals such as:

User Identity

Device Security Posture

Geographic Location

Application Risk Level
By evaluating these factors in real time, the system can grant, restrict, or deny access to sensitive applications and organizational resources.

The architecture is inspired by Zero Trust principles where every access request is continuously verified before authorization.

Key Features

Context-aware authentication and authorization

Identity-based access control using role and group membership

Device compliance verification before granting access

Location-based risk evaluation

Application risk classification

Secure micro-tunnel access to specific applications

Reduced attack surface through Zero Trust segmentation

Project Stages
Stage 1 – Manual Vulnerability Assessment

Manual web application security testing was conducted using industry-standard methodologies aligned with the OWASP Top 10.

Tools used:

Burp Suite

Manual testing techniques

Identified vulnerabilities include:

SQL Injection

Insecure Direct Object Reference (IDOR)

Weak Password Policy

Default Credentials

Insecure Deserialization

Lack of Rate Limiting

Weak Password Hashing

Detailed Error Message Disclosure

Missing Security Logging

These vulnerabilities demonstrate common weaknesses in web applications that attackers can exploit.

Stage 2 – Automated Vulnerability Scanning

Automated scanning was performed using Nessus Vulnerability Scanner to identify infrastructure and application vulnerabilities.

Target Environment:

Target Website: testfire.net

Target IP: 65.61.137.117

Key findings included:

Vulnerability	Severity
SQL Injection	Critical
Default Credentials	Critical
IDOR	High
Vulnerable Third-Party Libraries	High
Weak Password Hashing	High
Insecure Deserialization	High
Weak Password Policy	Medium
No Rate Limiting	Medium
Missing Security Logging	Medium
Detailed Error Messages	Low

These results highlight the importance of continuous vulnerability monitoring in modern security systems.

Stage 3 – SOC and SIEM Integration

The final stage focuses on security monitoring and incident response using SOC and SIEM concepts.

Topics explored:

Security Operations Center (SOC)

SIEM architecture and log correlation

Incident response lifecycle

Threat intelligence sharing

Security monitoring and detection

Tools studied:

IBM QRadar (SIEM platform)

MISP (Malware Information Sharing Platform)

These systems enable organizations to detect threats in real time, analyze logs, and respond to cyber incidents efficiently.

Technologies and Tools

Security Tools

Burp Suite

Nessus

Zscaler Private Access (ZPA)

Monitoring and Intelligence

IBM QRadar

MISP

Security Frameworks

Zero Trust Architecture (ZTA)

OWASP Top 10

NIST Security Principles

Use Case Scenarios

The project simulates real-world enterprise security situations such as:

Finance department accessing ERP systems

Contractors accessing project repositories

Executives accessing sensitive financial documents

Remote IT technicians troubleshooting internal systems

Employees accessing CRM from public networks

Each scenario demonstrates how context-aware policies dynamically adjust security controls.
Learning Outcomes

Through this project, the following cybersecurity concepts were explored:

Zero Trust Security Architecture

Vulnerability Assessment and Penetration Testing

Automated Security Scanning

Security Monitoring and Incident Response

Threat Intelligence Sharing

Context-aware access control mechanisms
Demo

A demonstration video of the project has been recorded showing:

Vulnerability testing

Nessus scanning results

Security analysis workflow

The demo video can be found here:

https://drive.google.com/file/d/1KTtut_wpeb_K2Y_7iqgYJwYy25nx37aJ/view?usp=sharing (Demo Video)
https://drive.google.com/file/d/1UQ9_iPN8_ouu7Us3WV4A8bmAYmxN6Men/view?usp=sharing (Screen Video of Nessus)

Team Members

Dharshini A (Team Lead)

Mythili K

Indhu C

Gnanashree P

Adharsh Vidhyalaya College of Arts and Science for Women

Conclusion

This project highlights how combining secure development practices, vulnerability management, 
and continuous monitoring can strengthen an organization’s cybersecurity posture. 
By applying Zero Trust principles and context-aware access control, 
organizations can significantly reduce the risk of unauthorized access and protect critical resources in modern distributed environments.
