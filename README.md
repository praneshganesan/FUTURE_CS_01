# Future Interns – Cybersecurity Task 1

## Vulnerability Assessment Report – DemoQA

This project documents a passive and non-intrusive vulnerability assessment performed on the publicly accessible DemoQA website.

### Objective

To identify potential security weaknesses through passive scanning, HTTP security-header analysis, and basic network reconnaissance, and document the findings with recommended remediation steps.

### Target

**Website:** DemoQA
**URL:** https://demoqa.com/

### Tools Used

* Nmap
* OWASP ZAP
* Browser Developer Tools
* Canva
* GitHub

### Methodology

The assessment used passive and non-intrusive security testing techniques.

OWASP ZAP was used for passive vulnerability analysis and Nmap was used for basic network reconnaissance and service identification.

No exploitation, brute-force attacks, authentication bypass, denial-of-service testing, or destructive activities were performed.

### Findings

| ID   | Finding                                         | Severity | Confidence |
| ---- | ----------------------------------------------- | -------- | ---------- |
| F-01 | Missing Content Security Policy                 | Medium   | High       |
| F-02 | Missing Anti-clickjacking Header                | Medium   | Medium     |
| F-03 | Vulnerable JavaScript Library – DOMPurify 3.2.6 | Medium   | Medium     |
| F-04 | Server Version Information Disclosure           | Low      | High       |
| F-05 | X-Powered-By Information Disclosure             | Low      | Medium     |
| F-06 | X-Content-Type-Options Header Missing           | Low      | Medium     |

### Evidence

Screenshots supporting the assessment findings are available in the `Evidence` folder.

### Assessment Notes

Supporting assessment notes are available in the `Notes` folder.

### Report

The complete professional vulnerability assessment report is available in the `Report` folder.

### Disclaimer

This assessment was performed for educational and internship purposes using non-intrusive security testing techniques. No attempt was made to exploit, disrupt, or gain unauthorized access to the target system.
