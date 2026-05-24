# Web Security Academy

> Hands-on exploitation writeups for every vulnerability category covered
> in PortSwigger's Web Security Academy — documented with full attacker
> methodology and defensive remediation guidance.

---

## About This Section

PortSwigger's Web Security Academy is one of the most respected free training
platforms in application security. This section documents every lab completed,
organized by vulnerability category, using a professional assessment format
that mirrors real-world penetration test reporting.

Each writeup goes beyond "how to solve the lab" — it explains the root cause,
the attacker's mindset, and how a developer should fix the vulnerability in
production code.

---

## Vulnerability Categories

| Category |
|---
| [SQL Injection](./SQL-Injection/) |
| [Cross-Site Scripting (XSS)](./XSS/) |
| [CSRF](./CSRF/) |
| [SSRF](./SSRF/) | 
| [XXE Injection](./XXE/) |
| [Access Control](./Access-Control/) |
| [Authentication](./Authentication/) |
| [Business Logic](./Business-Logic/) |
| [File Upload](./File-Upload/) |
| [OS Command Injection](./OS-Command-Injection/) |

---

## Lab Difficulty Key

| Badge | Level | Description |
|---|---|---|
| Apprentice | Beginner | Core concept, straightforward exploitation |
| Practitioner | Intermediate | Requires chaining techniques and deeper analysis |
| Expert | Advanced | Complex attack chains, real-world simulation |

---

## Assessment Format

Every lab writeup in this section follows this structure:

- Objective      — What the assessment aims to test
- Environment    — Tools, platform, and setup
- Reconnaissance — Information gathering methodology
- Vulnerability  — Root cause analysis
- Exploitation   — Step-by-step attack walkthrough
- Evidence       — Screenshots and payloads
- Impact         — What an attacker gains
- Remediation    — Secure coding fix with code examples
- References     — CVEs, CWEs, OWASP, and further reading

---

## Tools Used in This Section

| Tool | Purpose |
|---|---|
| Burp Suite Pro | HTTP interception, repeater, intruder |
| Browser DevTools | Client-side analysis and DOM inspection |
| SQLMap | Automated SQL injection testing |
| ffuf | Parameter and endpoint fuzzing |
| Kali Linux | Primary assessment operating system |

---

## References

- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [OWASP Testing Guide v4.2](https://owasp.org/www-project-web-security-testing-guide/)
- [OWASP Top 10 2021](https://owasp.org/Top10/)
- [CWE Top 25 Most Dangerous Software Weaknesses](https://cwe.mitre.org/top25/)

---

## Disclaimer

All labs documented here were completed exclusively within the PortSwigger
Web Security Academy authorized lab environment. No real-world systems
were tested without explicit permission.
