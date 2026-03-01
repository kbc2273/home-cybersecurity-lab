# Home Cybersecurity Lab – Vulnerability Exploitation & Detection Project

## Objective
Perform end-to-end vulnerability assessment within an isolated lab environment, including reconnaissance, vulnerability identification, exploitation, and post-exploitation validation.
---

## Overview
Built an isolated cybersecurity lab using VirtualBox consisting of an attacker machine (Kali Linux) and a vulnerable target system (Metasploitable2).

Conducted a full penetration testing workflow including network reconnaissance, service enumeration, vulnerability research, exploitation, and root-level access validation.

Documented findings and analyzed security risk impact based on discovered vulnerabilities.



---

## Lab Environment
- Host Machine: macOS
- Hypervisor: Oracle VirtualBox
- Attacker System: Kali Linux
- Target System: Metasploitable2
- Network Type: Host-Only Adapter (Isolated Environment)

---

## Assessment Process

### 1. Target Verification
Validated network connectivity between attacker and target systems.

### 2. Service Enumeration
Performed network scanning using Nmap to identify open ports and exposed services.

### 3. Vulnerability Identification
Researched detected services and identified vulnerable VSFTPD 2.3.4 FTP service.

### 4. Exploitation
Executed Metasploit Framework exploit targeting VSFTPD backdoor vulnerability.

### 5. Post-Exploitation Validation
Achieved root-level system access confirming successful compromise.


## Skills Demonstrated
- Network reconnaissance using Nmap
- Vulnerability research using Searchsploit
- Exploit execution using Metasploit Framework
- Linux command-line operations
- Privilege escalation validation
- Risk impact analysis
- Security documentation and reporting
---

## Evidence Screenshots

### 1. Lab Setup
![Lab Setup](images/01_lab-setup.png)

### 2. Target IP Verification
![Target IP](images/02_target-ip.png)

### 3. Nmap Service Enumeration
![Nmap Enumeration](images/03_nmap_enumeration.png)

### 4. Vulnerability Identification
![Vulnerability Identification](images/04_vulnerability-identification.png)

### 5. Metasploit Module Discovery
![Metasploit Modules](images/05_metasploit-module-discovery.png)

### 6. Exploit Attempt Execution
![Exploit Attempt](images/06_exploit-attempt.png)

### 7. Successful Remote Exploitation
![Successful Exploit](images/07_successful-exploit.png)

### 8. Root Access Proof
![Root Proof](images/08_root-proof.png)

---

## Report
Full vulnerability assessment report:

[Download Full Report](Home_Cybersecurity_Lab_Report.pdf)

---
## Key Outcomes
- Successfully compromised vulnerable system through identified service weakness
- Validated attacker visibility and system access
- Demonstrated practical penetration testing workflow
- Produced professional security assessment documentation


## Key Takeaways
- Demonstrated end-to-end penetration testing workflow
- Validated impact of unpatched services
- Documented remediation recommendations
