# 🎯 Penetration Testing  

## 📌 Overview  
As part of a **penetration testing course at the University of Maryland**, I conducted **host and network vulnerability assessments** on **four virtual machines (VMs)**, successfully exploiting weaknesses and capturing system flags. The project involved **enumeration, exploitation, credential extraction, and security risk mitigation**.  

---

## 🛠 Key Contributions  

- 🔍 **Assessed and attacked host and network vulnerabilities** across **four VMs**, navigating through each to **capture flags**.  
- 🚀 **Performed enumeration & exploitation** using **Metasploit Framework (MSF), Hydra, and Wireshark**.  
- 🔑 **Extracted hashed credentials** from **Linux and Windows services**, analyzing them for security weaknesses.  
- ⚡ **Executed real-world attack techniques**, including **brute-force attacks, privilege escalation, and service exploitation**.  
- 📜 **Provided a professional penetration testing report**, documenting **risks, vulnerabilities, and their security impact**.  
- 🛡 **Proposed a mitigation plan** to **improve the overall security posture** of the compromised machines.  

---

## 🛠 Tools & Technologies Used  

| Category                     | Tools & Technologies |
|------------------------------|----------------------|
| 🔍 Vulnerability Scanning    | Nmap, Nessus, Nikto |
| 🚀 Exploitation Frameworks   | Metasploit Framework (MSF) |
| 🔑 Credential Attacks        | Hydra, John the Ripper |
| 🏴‍☠️ Network Analysis       | Wireshark, tcpdump |
| 🖥 Windows & Linux Exploits  | Mimikatz, Linux Privilege Escalation Scripts |
| 📜 Reporting & Documentation | Penetration Testing Execution Standard (PTES) |

---

## ⚙️ Sample Exploits & Commands  

### 🔍 Scanning Target Network with Nmap  
```bash
nmap -A -T4 -p- 192.168.1.0/24
```
🚀 Exploiting a Linux SSH Service with Hydra
```bash
hydra -l admin -P rockyou.txt ssh://192.168.1.10
```
🔑 Extracting Hashed Credentials from a Windows Machine
```powershell
mimikatz "privilege::debug" "sekurlsa::logonpasswords" "exit"
```
🏴‍☠️ Capturing Network Traffic with Wireshark
```bash
sudo tcpdump -i eth0 -w capture.pcap
```

⸻

📋 Final Report & Evaluation

The project concluded with a comprehensive penetration testing report, detailing:

✅ Identified vulnerabilities across Windows and Linux VMs.
✅ Exploitation techniques used, including brute-force, privilege escalation, and credential extraction.
✅ Impact assessment of the discovered vulnerabilities.
✅ Proposed mitigation strategies to secure affected systems.
✅ Final submission & presentation, demonstrating real-world penetration testing methodologies.

⸻

🎤 Presentation & Impact

I compiled the findings and security weaknesses into a technical penetration testing report, outlining actionable security measures to harden system defenses.

⸻

💬 Have Questions?

Feel free to reach out or open an issue! 🚀🔐
