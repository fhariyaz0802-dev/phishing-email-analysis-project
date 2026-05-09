# Phishing Email Analysis Project

## Project Overview

This project focuses on identifying and analyzing phishing emails using real-world SOC Analyst techniques. The investigation was performed using [Google Admin Toolbox Messageheader](https://toolbox.googleapps.com/apps/messageheader/?utm_source=chatgpt.com) and [VirusTotal](https://www.virustotal.com?utm_source=chatgpt.com) to examine suspicious email headers, sender reputation, and malicious indicators.

## Objective

The goal of this project was to detect phishing indicators such as spoofed sender domains, SPF/DKIM/DMARC failures, suspicious IP addresses, and malicious email behavior to simulate real-world incident response.

## Tools Used

* [Google Admin Toolbox Messageheader](https://toolbox.googleapps.com/apps/messageheader/?utm_source=chatgpt.com)
* [VirusTotal](https://www.virustotal.com?utm_source=chatgpt.com)
* [AbuseIPDB](https://www.abuseipdb.com?utm_source=chatgpt.com)
* [MXToolbox](https://mxtoolbox.com?utm_source=chatgpt.com)

## Key Findings

* Fake sender domain detected: paypa1-security.com
* SPF failed → sender not authorized
* DKIM failed → email authenticity failed
* DMARC failed → domain spoofing likely
* Suspicious sender IP identified: 185.234.219.10
* VirusTotal showed the IP as unrated (0/92 detections), indicating low-reputation infrastructure often used in phishing campaigns

## Indicators of Compromise (IOCs)

| Type       | Value                                                             |
| ---------- | ----------------------------------------------------------------- |
| Domain     | paypa1-security.com                                               |
| IP Address | 185.234.219.10                                                    |
| Subject    | Urgent: Verify Your Account Immediately                           |
| Sender     | [support@paypa1-security.com](mailto:support@paypa1-security.com) |

## Incident Response Recommendations

* Block the malicious domain
* Monitor sender IP activity
* Educate users on phishing indicators
* Strengthen email filtering policies
* Enable advanced phishing detection rules

## Conclusion

This project demonstrates hands-on experience in phishing detection, email header analysis, IOC extraction, and incident reporting—core skills required for SOC Analyst and Cybersecurity internship roles.

