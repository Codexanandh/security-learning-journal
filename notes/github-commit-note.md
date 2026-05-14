docs: Day 1 – Web Security Lab Setup & First HTTP Interception

Set up a complete local web application security testing environment and performed
first hands-on traffic interception using Burp Suite.

Lab Environment:
- Kali Linux VM as primary security testing OS
- Burp Suite configured inside Kali for proxy interception
- Docker Desktop (Windows host) running OWASP Juice Shop locally
- Firefox browser routed through Burp Proxy

Activities Completed:
- Intercepted live HTTP/HTTPS traffic via Burp Suite Proxy
- Observed raw GET and POST requests in real time
- Analyzed request headers, parameters, and response structure
- Used Burp Repeater to resend and modify captured requests
- Verified full browser → proxy → server → response flow

Key Learnings:
- HTTP request lifecycle and how a proxy sits in the middle
- How sensitive data can appear in unprotected request bodies
- How request parameters can be manipulated to test server behavior
- Foundation mindset for input trust analysis in web security testing

Tools: Kali Linux | Burp Suite | Docker | OWASP Juice Shop | Firefox

Next: HTTP methods, cookies, sessions, auth flow, IDOR, parameter tampering
