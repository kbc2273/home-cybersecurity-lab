# Home Cybersecurity Lab – Vulnerability Exploitation Project

## Overview
I built an isolated cybersecurity lab using VirtualBox with an attacker machine (Kali Linux) and a vulnerable target system (Metasploitable2).

The goal was to simulate a real-world security assessment by performing reconnaissance, identifying vulnerabilities, exploiting a known weakness, and validating system compromise.

---

## Lab Environment
- Host Machine: macOS
- Hypervisor: Oracle VirtualBox
- Attacker System: Kali Linux
- Target System: Metasploitable2
- Network: Host-Only Adapter (isolated lab)

---

## Assessment Process

### 1. Target Verification
Confirmed network connectivity between attacker and target machines.

### 2. Service Enumeration
Used Nmap to identify open ports and running services.

### 3. Vulnerability Identification
Discovered vulnerable FTP service running VSFTPD 2.3.4.

### 4. Exploitation
Used Metasploit Framework to exploit the VSFTPD backdoor vulnerability.

### 5. Post-Exploitation Validation
Achieved root-level access and verified full system compromise.

---

## Evidence Screenshots
(See uploaded images in this repository)

---

## Report
Full vulnerability assessment report:

Home_Cybersecurity_Lab_Report_Watermarked_Korbin_Cartwright.pdf

---

## Key Takeaways
- Demonstrated end-to-end penetration testing workflow
- Validated impact of unpatched services
- Documented remediation recommendations
