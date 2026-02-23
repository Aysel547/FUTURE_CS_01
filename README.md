# Vulnerability Assessment Report - FUTURE_CS_01
View Presentation: https://www.canva.com/design/DAHCJLxNUZY/AFzckuDrWPHkiR1iFeOUcQ/view?utm_content=DAHCJLxNUZY&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h86bb56e6ad

##  Task Description
Conduct a vulnerability assessment on a live website using Nmap, OWASP ZAP, and Browser DevTools. Document findings in a professional report.

## Target
http://testphp.vulnweb.com

##  Tools Used
- Nmap (Network Scanning)
- OWASP ZAP (Passive Vulnerability Scanning)
- Browser DevTools (Manual Inspection)
- Canva (Report Design)

##  Key Findings Summary

| # | Vulnerability | Risk Level |
|---|---------------|------------|
| 1 | Hardcoded Credentials (test/test) | High |
| 2 | Missing Anti-CSRF Tokens | Medium |
| 3 | Missing CSP Header | Medium |
| 4 | Missing Anti-clickjacking Header | Medium |
| 5 | X-Powered-By Information Leak | Low |
| 6 | Server Version Disclosure | Low |
| 7 | Missing X-Content-Type-Options | Low |
| 8 | Charset Mismatch | Low |






