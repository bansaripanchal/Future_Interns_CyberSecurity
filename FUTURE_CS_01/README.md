# FUTURE_CS_01  
## Vulnerability Assessment Report  
**Internship:** Future Interns – Cyber Security Track (2026)

---

## 📌 Target Website
testphp.vulnweb.com  

---

## 🎯 Objective  
To perform a passive vulnerability assessment on a publicly accessible website and identify potential security misconfigurations and exposure risks.

---

## ⚖ Scope & Ethics  
- Public-facing pages only  
- Passive analysis only  
- No exploitation performed  
- No login bypass attempts  
- No intrusive testing  

This assessment was conducted strictly within ethical and read-only boundaries.

---

## 🛠 Tools Used  
- Nmap (Port & Service Analysis)  
- OWASP ZAP (Passive Vulnerability Scan)  
- Browser Developer Tools (Header Inspection)  
- Canva (Report Design & Documentation)

---

## 🔎 Methodology  
1. Selected a public demo website for analysis  
2. Conducted reconnaissance using Nmap  
3. Performed passive vulnerability scanning using OWASP ZAP  
4. Analyzed HTTP response headers  
5. Documented identified security weaknesses  
6. Classified risks (Low / Medium)  
7. Provided business-friendly remediation recommendations  

---

## ⚠ Summary of Findings  

The assessment identified configuration-related security weaknesses, including:

- Missing Content Security Policy (CSP) Header  
- Missing Anti-Clickjacking Header  
- Absence of Anti-CSRF Tokens  
- Server Version Disclosure  
- Missing X-Content-Type-Options Header  
- Charset Mismatch  

No critical vulnerabilities were identified during this passive assessment.

---

## 🛡 Risk Classification  

- High: 0  
- Medium: 3  
- Low: 3  
- Informational: 1  

---

## ✅ Remediation Overview  

Key recommendations include:

- Implement proper security headers (CSP, X-Frame-Options, X-Content-Type-Options)  
- Remove server version information from HTTP headers  
- Implement Anti-CSRF protection mechanisms  
- Ensure consistent charset configuration  

Addressing these issues will significantly strengthen the website’s security posture.

---

## 📂 Repository Contents  

- Vulnerability Assessment Report (PDF)  
- Nmap Scan Evidence  
- OWASP ZAP Scan Screenshots  
- Risk Classification Summary  

---

## 👩‍💻 Intern  

Bansari Panchal  
M.Sc IT – Cyber Security  
Future Interns – 2026
