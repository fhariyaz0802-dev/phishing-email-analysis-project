# Phishing Email Analysis Project

## Project Overview

This project demonstrates phishing email investigation using email header analysis and threat intelligence tools. The goal was to identify phishing indicators such as spoofed sender domains, SPF/DKIM/DMARC failures, suspicious IP addresses, and malicious email behavior.

## Tools Used

- Google Admin Toolbox Messageheader
- VirusTotal
- AbuseIPDB
- MXToolbox

## Key Findings

- Fake sender domain detected: paypa1-security.com
- SPF = Fail
- DKIM = Fail
- DMARC = Fail
- Suspicious sender IP identified: 185.234.219.10
- VirusTotal showed IP as unrated (0/92 detections)

## Indicators of Compromise (IOCs)

| Type | Value |
|---|---|
| Domain | paypa1-security.com |
| IP Address | 185.234.219.10 |
| Sender Email | support@paypa1-security.com |
| Subject | Urgent: Verify Your Account Immediately |

## Incident Response Recommendations

- Block malicious domain
- Monitor suspicious IP activity
- Educate users on phishing indicators
- Strengthen email security policies
- Enable advanced phishing detection rules

## Conclusion

This project demonstrates practical SOC Analyst skills in phishing detection, email header analysis, IOC extraction, and incident reporting.
