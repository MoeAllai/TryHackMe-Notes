# Splunk: Basics – TryHackMe Notes

🧠 Objective: Learn how to use Splunk for searching, analyzing, and visualizing logs in a SOC environment.

---

## Key Concepts

- SPL (Search Processing Language):  
  Language used to query logs within Splunk

- Index:  
  Storage location for logs (e.g., main, windows, linux)

- Source Type:  
  Format/type of the data (e.g., WinEventLog, syslog)

- Search Bar Basics:  
  index=windows sourcetype=WinEventLog:Security EventCode=4624

---

## Useful SPL Commands

- stats count by EventCode  
- table _time, user, EventCode  
- sort - _time  
- top process_name  
- eval, where, dedup, regex

---

## Lessons Learned

- How to search for failed logins (EventCode 4625)  
- Understand how logs are structured and indexed  
- Customize dashboards with visualizations

---

Room Link: https://tryhackme.com/room/splunkintro
