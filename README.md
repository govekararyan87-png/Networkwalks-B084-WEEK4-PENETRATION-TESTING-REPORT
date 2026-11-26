# 🏥 Mediroza General Hospital – Web Infrastructure Security Assessment

![Security Assessment](https://img.shields.io/badge/Project-Penetration%20Testing-blue)
![Batch](https://img.shields.io/badge/Batch-B084-orange)
![Week](https://img.shields.io/badge/Week-04-purple)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Classification](https://img.shields.io/badge/Classification-Confidential-red)

## 📌 Project Information

| Details | Information |
|---|---|
| **Project Title** | Penetration Testing Project – Mediroza General Hospital |
| **Tester Name** | Aryan Govekar |
| **Batch / Week** | B084 / Week 4 |
| **Assessment Dates** | 25 November 2026 – 26 November 2026 |
| **Target Domain** | https://medirozahospital.com |
| **Report Date** | 26 November 2026 |
| **Assessment Type** | Black-Box Penetration Testing |
| **Classification** | Confidential – Authorized Personnel Only |

---

## 1. 📖 Executive Summary

This project involved a black-box penetration testing assessment of the web infrastructure of Mediroza General Hospital.

The assessment was conducted under authorized testing conditions and strictly followed the defined scope of work.

The engagement focused on identifying security weaknesses, evaluating potential risks, and documenting vulnerabilities affecting the target web application.

The assessment identified several security issues, including:

- SQL Injection vulnerability in the patient portal.
- Weak authentication credentials.
- Exposure of a historical database backup.
- Weak PDF document encryption.
- Directory listing enabled.
- Username enumeration.

The findings demonstrated potential risks to patient confidentiality, employee information, and organizational data security.

All four project milestones were completed, with supporting technical evidence documented in the respective folders.

---

## 2. 🚨 Risk Rating Summary

| Vulnerability | Severity | CVSS Score | Status |
|---|---|---|---|
| SQL Injection – Authentication Bypass | Critical | 9.8 | Exploited |
| Weak Default Credentials | High | 7.5 | Identified |
| Exposed Database Backup | High | 7.5 | Verified |
| Weak PDF Encryption | High | 7.4 | Verified |
| Directory Listing Enabled | Medium | 5.3 | Identified |
| Username Enumeration | Low | 3.7 | Identified |

---

## 3. 🔍 Key Security Findings

### 3.1 SQL Injection (SQLi)
- Identified an SQL Injection vulnerability in the patient login functionality.
- Authentication controls were found to be vulnerable.
- Demonstrated the potential for unauthorized access.

### 3.2 Weak Authentication Credentials
- Identified weak/default authentication credentials.
- Demonstrated the importance of enforcing strong password policies.

### 3.3 Exposed Database Backup
- Discovered an accessible historical database backup.
- The backup presented a risk of exposure of employee and shareholder information.

### 3.4 Weak PDF Encryption
- Identified weak password protection on retrieved PDF documents.
- Demonstrated the importance of strong document encryption.

### 3.5 Directory Listing
- Identified directory listing exposure.
- Recommended disabling directory indexing across the web server.

### 3.6 Username Enumeration
- Identified authentication responses that could reveal valid usernames.
- Recommended implementing generic login error messages.

---

## 4. 📂 Project Folder Structure

The submission is organized into four milestones for easy verification.

```text
Mediroza-Penetration-Testing/
│
├── M1_Access_and_PDFs/
│   ├── mediroza_results.json
│   ├── bypass_success.html
│   ├── patient_report_001.pdf
│   ├── patient_report_002.pdf
│   ├── patient_report_003.pdf
│   └── Screenshots/
│
├── M2_Cracked_PDFs/
│   ├── rep1.txt
│   ├── rep2.txt
│   ├── rep3.txt
│   └── Screenshots/
│
├── M3_Data_Exposure/
│   ├── full_backup.sql
│   └── Screenshots/
│
├── M4_Report/
│   └── Mediroza_Pentest_Report_FINAL.pdf
│
└── README.md
```

**Note:** Sensitive evidence files are intentionally excluded from the public repository.

---

## 5. 🎯 Milestone Completion Status

| Milestone | Description | Status |
|---|---|---|
| M1 | Website assessment and identification of confidential PDF exposure | ✅ Completed |
| M2 | Assessment of PDF encryption strength | ✅ Completed |
| M3 | Identification and verification of database information exposure | ✅ Completed |
| M4 | Preparation of the final penetration testing report | ✅ Completed |

---

## 6. 🛠️ Methodology

The assessment followed a structured penetration testing workflow:

1. **Reconnaissance:** Gathered information about the target web infrastructure.
2. **Enumeration:** Identified accessible resources and potential attack surfaces.
3. **Vulnerability Assessment:** Tested authentication, input validation, and access controls.
4. **Controlled Exploitation:** Validated identified vulnerabilities within the authorized scope.
5. **Evidence Collection:** Documented findings using screenshots and technical evidence.
6. **Reporting:** Prepared a detailed report with findings and remediation recommendations.

---

## 7. 🛡️ Remediation Recommendations

| Finding | Recommended Remediation |
|---|---|
| SQL Injection | Implement parameterized queries and prepared statements. |
| Weak Credentials | Enforce strong passwords and multi-factor authentication. |
| Exposed Database Backup | Remove publicly accessible backups and restrict access to sensitive files. |
| Weak PDF Encryption | Use strong encryption and secure document password management. |
| Directory Listing | Disable directory indexing on the web server. |
| Username Enumeration | Use generic authentication error messages and rate limiting. |

---

## 8. 📑 Final Penetration Testing Report

The complete penetration testing report contains:

- Detailed vulnerability descriptions.
- Testing methodology.
- Technical findings.
- Proof-of-concept documentation.
- Supporting evidence references.
- Risk assessments.
- Recommended remediation steps.

**Report File:** `M4_Report/Mediroza_Pentest_Report_FINAL.pdf`

---

## 9. 📸 Attached Evidence

Supporting evidence is organized by milestone:

- **M1:** Authentication assessment and document access evidence.
- **M2:** PDF encryption assessment evidence.
- **M3:** Database exposure assessment evidence.
- **M4:** Final penetration testing report.

Refer to the corresponding milestone folders in the authorized evidence archive.

---

## 10. ⚠️ Disclaimer

This project was conducted as an authorized cybersecurity assessment for educational and security evaluation purposes.

All testing activities were intended to remain within the defined scope of authorization.

The findings are documented to demonstrate security weaknesses and recommend appropriate remediation measures.

**Confidentiality Notice:** This assessment may involve sensitive healthcare, employee, and organizational information. Actual patient records, credentials, personal identifiers, and confidential database contents must not be published in a public repository.

---

## 👨‍💻 Project Credits

**Tester:** Aryan Govekar  
**Batch:** B084  
**Week:** 4  
**Project:** Mediroza General Hospital – Web Infrastructure Security Assessment

**End of Report**
