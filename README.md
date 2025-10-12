# itsecgames.com-assignment.-
# 🛡️ Assessment – itsecgames.com  

**Prepared by:** Aakash Dagadu Patil  

---

## 🎯 Objective  
Evaluate the security posture of **(http://www.itsecgames.com)** by identifying vulnerabilities, outdated software, and SSL/TLS configuration issues using open-source tools.

---

## 🧰 Tools Used  
Nmap, Nikto, OWASP ZAP, Netcraft, SearchSploit, Smart Scanner, cURL, whois, dig, etc.

---

## 🔍 Key Findings  

| Severity  | Issue                                           | Tool |
|------------|------------------------------------------------|-------|
| 🟠 Medium | Missing security headers (CSP, X-Frame-Options) | Nikto, ZAP |
| 🟡 Low    | Outdated OpenSSH 6.7p1                          | Nmap |
| 🟢 Info   | SSL hostname mismatch                           | Netcraft  |
| 🟢 Info   | Public WHOIS/DNS info visible                   | Whois |

---

## 🩵 Recommendations  
- Implement **CSP** and **X-Frame-Options** headers  
- Upgrade **OpenSSH** to the latest stable version  
- Fix **SSL hostname mismatch**  
- Limit exposure of server version and domain details  

---

## 📂 Project Structure  
report/
└─ Final report of itsecgames.com.pdf

scans/
├─ Check headers
├─ Port & service discovery (nmap)
├─ SSL TLS certificate health
├─ WHOIS lookup
└─ cve/
└─ vulnerability checks

screenshots/

README.md

📄 [View Full Report] (report/Final report of itsecgames.com.pdf)  
📧 Contact: akakashpatil7777@gmail.com  

