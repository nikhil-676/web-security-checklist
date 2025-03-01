# web-security-checklist
A checklist of common web application security vulnerabilities and tests.
# 🛡️ Web Application Security Checklist  

A comprehensive checklist for web security testing, covering OWASP Top 10 vulnerabilities and beyond.  

## 🔹 Authentication & Authorization  
✅ Ensure strong password policies (min. 12 characters, mix of upper/lowercase, numbers, special chars)  
✅ Implement multi-factor authentication (MFA)  
✅ Secure authentication using HTTPS only (no HTTP login)  
✅ Prevent brute-force attacks (account lockout, CAPTCHA)  
✅ Verify role-based access control (RBAC) permissions  

## 🔹 Input Validation & Injection  
✅ Validate and sanitize all user inputs  
✅ Prevent SQL Injection (use parameterized queries, ORM)  
✅ Block XSS (use Content Security Policy, escape outputs)  
✅ Restrict file uploads (check MIME type, size, and content)  

## 🔹 API & Backend Security  
✅ Use authentication tokens (JWT, OAuth) securely  
✅ Rate-limit API requests to prevent abuse  
✅ Implement proper CORS policies  
✅ Hide sensitive error messages  

## 🔹 Data Protection & Encryption  
✅ Store passwords using bcrypt or Argon2 (never plain text)  
✅ Use HTTPS with HSTS enabled  
✅ Encrypt sensitive data at rest and in transit  

## 🔹 Server & Infrastructure Security  
✅ Disable directory listing and unnecessary HTTP methods  
✅ Keep software and dependencies updated  
✅ Secure database configurations (disable remote access, least privilege)  
✅ Regularly backup critical data  

## 🛠️ Tools for Security Testing  
- **Burp Suite** – Intercept & analyze HTTP traffic  
- **OWASP ZAP** – Automated security scanning  
- **Nikto** – Web server scanner  
- **SQLmap** – SQL Injection detection & exploitation  
- **Wfuzz** – Fuzzing tool for brute force attacks  

📌 **More resources:** [OWASP Top 10](https://owasp.org/www-project-top-ten/)  

