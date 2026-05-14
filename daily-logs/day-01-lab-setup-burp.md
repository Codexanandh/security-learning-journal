# 🔐 Web Security Learning Log — Day 01

**Date:** Day 1  
**Author:** Anandha Kumar B  
**GitHub:** [github.com/Codexanandh](https://github.com/Codexanandh)  
**LinkedIn:** [linkedin.com/in/anandha-kumar-b-b6b637298](https://www.linkedin.com/in/anandha-kumar-b-b6b637298/)  
**Focus Area:** Web Application Security · Bug Bounty · VAPT  
**Status:** ✅ Completed  
**Screenshot/Recording:** 🔜 Recording planned from Day 2 onwards

---

## 🧠 Overview

Completed the initial setup of a local web application security lab and performed hands-on HTTP traffic interception using Burp Suite. This is Day 1 of a structured, practical journey into web security and bug bounty hunting — learning by doing, not just reading.

---

## 🛠️ Lab Environment

| Component | Details |
|-----------|---------|
| OS | Kali Linux (VM) — primary security testing environment |
| Proxy Tool | Burp Suite — installed and configured inside Kali |
| Host System | Windows with Docker Desktop |
| Target App | OWASP Juice Shop — deployed locally via Docker |
| Browser | Firefox — routed through Burp Proxy |

> This setup gives full control over request interception, modification, and analysis in a safe, legal, isolated environment.

---

## 🌐 Hands-On Activities

- [x] Intercepted live HTTP and HTTPS traffic via Burp Suite Proxy
- [x] Observed raw GET and POST requests between browser and server
- [x] Analyzed request headers, URL parameters, and response structures
- [x] Used Burp Repeater to resend and modify captured requests
- [x] Verified the full browser → proxy → server → response traffic flow
- [x] Interacted with OWASP Juice Shop while monitoring traffic in real time

---

## 🔍 Key Technical Observations

1. **HTTP is structured communication** — every action in a web app generates a readable request with headers, method, body, and parameters.
2. **Sensitive data can leak through request bodies** — if not properly secured, credentials and tokens appear in plaintext.
3. **Burp Suite sits in the middle** — it intercepts traffic before it reaches the server, allowing full visibility and modification.
4. **Parameters can be manipulated** — changing values in requests often produces unexpected or unintended server behavior.
5. **Proxy flow is fundamental** — understanding browser → proxy → server → response is the baseline of web security testing.

---

## 🎯 Learning Outcomes

- Understood the complete HTTP request lifecycle from a security perspective
- Learned how an interception proxy works in real time
- Got first hands-on experience with Burp Repeater for request modification
- Began developing the security tester's mindset: *"What does the server trust? Should it?"*

---

## 🚀 Next Steps (Day 2+)

- [ ] Study HTTP methods in depth (GET, POST, PUT, DELETE, OPTIONS)
- [ ] Learn cookies, sessions, and authentication flows
- [ ] Practice IDOR (Insecure Direct Object Reference) testing
- [ ] Explore input validation vulnerabilities in OWASP Juice Shop
- [ ] Begin structured Burp Suite vulnerability testing methodology
- [ ] Start documenting findings in professional report format
- [ ] Record screen from Day 2 for visual portfolio proof

---

## 📌 Tools Used

- **Kali Linux** — Security-focused Linux distribution
- **Burp Suite** — Industry-standard web proxy and security testing platform
- **Docker Desktop** — Container runtime (Windows host)
- **OWASP Juice Shop** — Intentionally vulnerable Node.js web application
- **Firefox** — Configured with manual proxy settings pointing to Burp

---

## 📈 Progress Note

> This is **Day 1 of 30** in a structured, self-directed web application security learning plan. The goal is to progress from foundational traffic understanding → vulnerability identification → real-world security testing methodology — documented publicly every step of the way.

---

*Learning in public. Building real skills. One day at a time.*
