ETHICAL HACKING INTERNSHIP - FINAL SUBMISSION
=============================================

This README file includes the summary of all three tasks completed as part of the Ethical Hacking Internship.

------------------------------------------------------------
Task 1: PortSwigger Labs - Web Security Academy
------------------------------------------------------------
Description:
Solved several labs provided by PortSwigger Web Security Academy to enhance practical web application security skills.

What’s Included:
- Screenshots of completed labs demonstrating:
  * Reflected XSS
  * Stored XSS
  * DOM-Based XSS

Note:
Each screenshot clearly shows the lab marked as "Solved".

------------------------------------------------------------
Task 2: Netsparker Vulnerability Scanning
------------------------------------------------------------
Description:
Scanned the target website http://testasp.vulnweb.com/ using Netsparker (now known as Invicti) to identify web vulnerabilities.

Findings:
- Example Vulnerability: Password Transmitted Over HTTP (HIGH)
  * URL: http://testasp.vulnweb.com/Login.asp
  * Input Name: tfUPass
  * Risk: Login credentials are being transmitted over insecure HTTP.
  * CVSS 3.1 Score: 5.7 (Medium)
  * OWASP 2017: A3 Sensitive Data Exposure
  * Remedy: Move all sensitive forms to HTTPS

What’s Included:
- Screenshots of Netsparker scans
- Auto-generated Netsparker report
- A written report comparing the actual and scanned results in the presentation slides

------------------------------------------------------------
Task 3: Manual Vulnerability Testing and Reporting
------------------------------------------------------------
Target: http://testasp.vulnweb.com/

Methodology:
- Manually inspected the login form
- Intercepted HTTP requests using Burp Suite
- Observed that login credentials (username and password) are visible in plaintext over HTTP

Proof:
- Screenshot 1: Login form with credentials filled
- Screenshot 2: Intercepted HTTP request in Burp Suite showing the password in plaintext
- Attached Presentation includes:
  * Vulnerability summary
  * Manual test steps
  * Screenshots
  * CVSS score and impact analysis
  * Remedy

------------------------------------------------------------
Submission Method
------------------------------------------------------------
- All files (screenshots, reports, videos, presentations) are uploaded to GitHub repository as per instructions.

GitHub Repository Link: https://github.com/cb346666/Ethical-Hacking-Internship-2025.git

------------------------------------------------------------
Prepared By:
(Chauhan Brijeshkumar)
Ethical Hacking Internship Participant
