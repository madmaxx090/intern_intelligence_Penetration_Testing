# OWASP Juice Shop Penetration Test Report

This repository contains a detailed penetration testing report conducted on the OWASP Juice Shop application using Kali Linux. The objective of this test was to identify and exploit common web application vulnerabilities in a safe and controlled environment. Tools used include Burp Suite, OWASP ZAP, browser developer tools, and manual testing techniques.

## Report Highlights
- **SQL Injection:** Authentication bypass and unauthorized database access via unsanitized input.
- **Cross-Site Scripting (XSS):** Both Reflected and DOM-based XSS vulnerabilities allowing script injection.
- **Broken Authentication:** Weak password reset mechanisms and predictable security questions exploited for account takeover.
- **Admin Access Exploits:** Gained full control of the application through credential exposure and known login flaws.
- **Insecure Data Transmission:** Plaintext credentials captured over HTTP due to lack of encryption.
- **Misconfigured CORS:** Overly permissive CORS policy potentially allowing data theft from unauthorized domains.
- **Insecure File Disclosure:** Sensitive files such as `.git`, logs, and backups were accessible via the web server.
- **Weak Cryptography:** Use of insecure or custom cryptographic implementations vulnerable to token forgery.

## Tools & Environment
- **Operating System:** Kali Linux
- **Primary Tools:** Burp Suite, OWASP ZAP, Developer Tools, curl
- **Target:** OWASP Juice Shop (http://localhost:3000)
- **Test Type:** Black-box, authorized penetration testing

## Purpose of This Report
This penetration test was conducted for **educational and training purposes**. The OWASP Juice Shop is a deliberately vulnerable web app designed to help students and professionals learn web security concepts through hands-on experience. The findings outlined in the report reflect common real-world security issues, emphasizing the importance of secure coding practices, strong authentication, proper input validation, and encryption.

## Disclaimer
> ⚠️ This report and associated files are for **educational and ethical** use only. All tests were performed in a **local lab environment** using intentionally vulnerable software. Do not attempt similar testing on live systems without proper authorization.

## Author
- Unaiza fatima 

- Penetration Tester | Cybersecurity Enthusiast

---


