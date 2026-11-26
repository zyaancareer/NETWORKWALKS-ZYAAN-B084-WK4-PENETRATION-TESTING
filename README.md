# Hospital Penetration Testing Report

# Project Overview

This project involved a penetration testing assessment of a deliberately vulnerable hospital web application. The objective was to identify security weaknesses, investigate potential entry points and assess the exposure of confidential information.

# Objectives

- Perform network reconnaissance.
- Identify open ports and running services.
- Investigate web application directories.
- Test portal authentication and input handling.
- Identify exposed files and sensitive information.
- Document findings and recommend security improvements.

# Tools Used

Tool| Purpose
Kali Linux| Cybersecurity testing environment.
Nmap / Zenmap| Network scanning and service discovery.
Web Browser| Website navigation, portal testing and directory investigation.
Text Editor| Examination of the exposed SQL database backup.

# Key Findings

1. SQL Injection: Successfully gained access to the Patient Portal through an SQL injection vulnerability.
2. Information Disclosure: The "robots.txt" file revealed additional website directories.
3. Exposed Directory: Discovered a publicly accessible "/old/" directory.
4. Exposed Database Backup: Located an SQL database backup containing hospital employee and shareholder information.

# Recommendations

- Implement parameterised SQL queries.
- Strengthen authentication and input validation.
- Disable public directory listing.
- Remove database backups from publicly accessible directories.
- Apply appropriate access controls to confidential information.

# Project Documentation

The full assessment, including findings, risk analysis and recommendations, is available in:

"Hospital_Penetration_Testing_Report.pdf"

Disclaimer

This project was conducted for educational purposes within the scope of an assigned cybersecurity exercise.

Sensitive information discovered during testing has been excluded or redacted from this public repository.
