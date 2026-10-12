# Web Application & API Penetration Test
 
**Digital Egypt Pioneers (رواد مصر الرقمية) - Graduation Project**

Track: Vulnerability Analyst / Penetration Tester

Project 2: Web Application & API Penetration Test
 
---
 
## Overview
 
A 4-week penetration testing project against an intentionally vulnerable, legally authorized target. The work covers web fundamentals and Burp Suite setup, input-based vulnerabilities, authentication/session/access control and API testing, and finally attack chaining, reporting and retesting.
 
**Target application:** OWASP Juice Shop / DVWA / PortSwigger Web Security Academy - to be decided.
 
> All testing is done only on intentionally vulnerable labs and applications we are authorized to test. No real-world systems are targeted.
 
---
 
## Team
 
| #   | Name                                   | Role / Focus                   |  GitHub                                                     |
| --- | -------------------------------------- | ------------------------------ | ----------------------------------------------------------  |
| 1   |   Muhammad Saleh Fetouh Elsayad         | Team Lead / Reporting          | [elsayadm901-1211](https://github.com/elsayadm901-1211)     |
| 2   |  Abdallah Mohammed Elsayed Elkorashy   | Input-Based Vulnerabilities    | [abdallahelkorashy](https://github.com/abdallahelkorashy)   |
| 3   |   Omar Elbakry Yehia Elbakry Yehia     | Auth, Session & Access Control | [Omar-Elbakry-Yehia](https://github.com/Omar-Elbakry-Yehia) |
| 4   |   Mazen Nabil Mohammed Alrasi          | API Testing & Retest           | [mazenalrasi1](https://github.com/mazenalrasi1)             |
 
---
 
## Project Plan
 
| Week | Focus                               | Main Deliverables                                                                                              |
| ---- | ----------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| 1    | Web Fundamentals & Burp Setup       | Application map, Burp project file, request/response inventory, auth/session flow diagram, test plan           |
| 2    | Input-Based Vulnerabilities         | PoC per vulnerability, payload list, screenshots/evidence, CVSS scores, remediation notes                      |
| 3    | Auth, Session, Access Control & API | API test collection, API findings report, IDOR/BOLA PoCs, auth/session findings, impact statements             |
| 4    | Chaining, Reporting & Retest        | Final Web/API pentest report, attack chain diagram, retest checklist, remediation plan, demo video/screenshots |
 
---
 
## Repository Structure
 
```
web-api-pentest-project/
├── week1-fundamentals-burp-setup/
├── week2-input-based-vulnerabilities/
├── week3-auth-session-access-control-api/
└── week4-chaining-reporting-retest/
```
 
Each week folder contains one sub-folder per deliverable.
 
---
 
## Tools
 
- Burp Suite (Proxy, Repeater, Intruder, Site map)
- Postman or similar for API testing
- OWASP Juice Shop / DVWA / PortSwigger labs
- CVSS calculator for severity scoring
 
---
 
## Workflow & Contribution Rules
 
1. Never push directly to `main`. Work on your own branch and open a Pull Request.
2. Branch naming: `week<N>/<your-name>/<short-task>` (example: `week2/ahmed/sqli-poc`).
3. Commit messages: short and clear, starting with a verb (example: `Add XSS PoC and screenshots`).
4. At least one teammate reviews each Pull Request before merging.
5. Each finding should include: title, affected endpoint, steps to reproduce, evidence, CVSS score, impact, and remediation.
 
### Security hygiene
 
- Do not commit real credentials, tokens, or cookies. Sanitize Burp project files and screenshots before uploading.
- Large files (Burp projects, videos) should be reviewed before pushing or shared through a drive link instead.
 
---
 
## Status
 
- [ ] Week 1
- [ ] Week 2
- [ ] Week 3
- [ ] Week 4
 
---
 
## Disclaimer
 
This project is for educational purposes only as part of the Digital Egypt Pioneers program. Testing is limited to authorized, intentionally vulnerable targets.
 
