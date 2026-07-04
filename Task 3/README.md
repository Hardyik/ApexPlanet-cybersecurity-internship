# Task-3: Web Application Security

**Student Name:** Hardik Prakash Kotawdekar  
**Offer Letter ID:** APSPL2635998  
**Date:** 28 Jun 26
**Status:** Completed ✅

## 🎯 Objective
Identify and exploit OWASP Top 10 vulnerabilities in DVWA (Damn Vulnerable Web Application) at Low security level.

---

## 🛠️ Tools Used
- Kali Linux + Metasploitable2
- DVWA (Damn Vulnerable Web App)
- Burp Suite

---

## 📋 Exploits Performed

### 1. SQL Injection
- Used UNION-based injection to dump `users` table.
- Successfully retrieved usernames and passwords (including admin).

### 2. Cross-Site Scripting (XSS)
- Stored XSS: Executed alert script.
- Reflected XSS: Demonstrated via query parameters.

### 3. Cross-Site Request Forgery (CSRF)
- Created malicious HTML form to change user password without consent.

### 4. File Inclusion
- Local File Inclusion (LFI): Read system files like `/etc/passwd`.

### 5. Burp Suite
- Intercepted and modified login requests.
- Performed basic parameter fuzzing with Intruder.

---

## 📸 Screenshots
All screenshots are available in the `Screenshots/` folder.

---

## 📄 Report
- Full Security Testing Report (PDF/Word) attached.

---

## 🎥 Demo Video
**Duration:** ~8 minutes  
**Link:** [Watch](https://www.linkedin.com/posts/hardik-kotawdekar-b22482329_cybersecurity-ethicalhacking-websecurity-ugcPost-7479091916387540992-PBsn/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFLUW8oBxyNTJhfns_G_BcIM-rUE3eklagg)

---

**Prepared by:** Hardik Prakash Kotawdekar  
**ApexPlanet Cybersecurity & Ethical Hacking Internship**
