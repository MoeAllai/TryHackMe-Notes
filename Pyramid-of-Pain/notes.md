# Pyramid of Pain – TryHackMe Notes

🧠 Objective: Understand how different indicators of compromise (IOCs) impact the difficulty of threat detection and adversary disruption.

---

## 🧱 Levels of the Pyramid (from weakest to strongest)

1. **Hash Values (e.g., MD5, SHA1)**  
   Easiest to detect/block, but also easiest to bypass (change the file slightly)

2. **IP Addresses**  
   Can be blocked, but attackers rotate often

3. **Domain Names**  
   Slightly more persistent than IPs, but still easily changed

4. **Network/Host Artifacts**  
   E.g., specific User-Agent strings, unusual registry keys

5. **Tools**  
   Actual tools used by attackers (e.g., Mimikatz)

6. **TTPs (Tactics, Techniques, and Procedures)**  
   The attacker’s behavior pattern — hardest to change and **most powerful to detect**

---

## 🔍 Real-World Insight

- Targeting **TTPs** is the best strategy for durable detection
- Don’t rely only on hash or IP blacklists — they’re fragile
- Use MITRE ATT&CK to map and track adversary behavior

---

🎯 Room Link: https://tryhackme.com/room/pyramidofpain
