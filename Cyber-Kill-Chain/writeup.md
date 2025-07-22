# Cyber Kill Chain – TryHackMe Notes

🧠 **Objective:** Understand how attackers move from reconnaissance to actions on objectives using Lockheed Martin’s Cyber Kill Chain model.

## ✅ Key Stages

1. **Reconnaissance**  
   Gathered public data, scanned target

2. **Weaponization**  
   Created malicious payload

3. **Delivery**  
   Sent via phishing/email

4. **Exploitation**  
   Used browser exploit or CVE

5. **Installation**  
   Dropped malicious executable

6. **Command & Control (C2)**  
   Established backdoor to attacker’s server

7. **Actions on Objectives**  
   Data exfiltration, persistence

---

## 🔍 Tools used
- Wireshark
- Strings
- netstat
- nslookup

## 💡 Lessons Learned
- Analyze PCAPs to track malware delivery path
- Identify C2 via port and country lookup
- Kill chain gives visibility at every phase of attack

---

🎯 Room Link: https://tryhackme.com/room/cyberkillchain
