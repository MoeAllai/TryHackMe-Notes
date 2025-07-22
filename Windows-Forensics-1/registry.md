# Windows Forensics 1 – Registry Analysis

🧠 Objective: Extract evidence and insights from Windows registry hives using forensic tools.

---

## 📁 Registry Hives Analyzed

- **SAM:** Contains local user accounts  
- **SYSTEM:** Holds system boot info, services, network settings  
- **NTUSER.DAT:** Stores user-specific settings (recent files, run history)

---

## 🛠️ Tools Used

- Registry Explorer
- Autoruns
- FTK Imager (optional for mount/export)
- CyberChef (for decoding values)

---

## 🔍 Notable Artifacts

### From `NTUSER.DAT`
- **UserAssist:** Shows apps run by the user (ROT13 encoded)
- **RunMRU:** Lists items typed in Run box
- **RecentDocs:** Tracks recently opened documents

### From `SAM`
- List of all local user accounts
- Password hint, if set

### From `SYSTEM`
- Time zone settings
- Mounted devices
- Network interfaces

---

## 💡 Lessons Learned

- Registry hives are a goldmine for user activity and persistence techniques
- Tools like Registry Explorer make deep analysis accessible
- Timestamps (LastWrite) reveal hidden activity

---

🎯 Room Link: https://tryhackme.com/room/windowsforensics1
