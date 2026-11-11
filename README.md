# NetworkWalks — Week 2 Cybersecurity Internship

**Intern:** Taha Chebil  
**Batch:** B084  
**Program:** Cybersecurity & Ethical Hacking  
**Week:** 2 — Footprinting, Reconnaissance & Network Scanning  
**Status:** W2-PM1 and W2-PM5 completed; final report prepared.

## Overview

This repository documents my Week 2 hands-on cybersecurity internship activities. I completed one elective module (**W2-PM1**) and the mandatory network scanning module (**W2-PM5**), then prepared a final assessment report (**W2-PM-FINAL**).

The exercises focused on information gathering and host discovery. **No exploitation, credential attacks, or denial-of-service testing was performed.**

## Completed modules

| Module | Focus | Outcome | Documentation |
|---|---|---|---|
| W2-PM1 | Footprinting with six Kali Linux tools | 6/6 tasks completed | [PM1 notes](W2-PM1/README.md) |
| W2-PM5 | Network scanning using Zenmap | 7/7 tasks completed | [PM5 notes](W2-PM5/README.md) |
| W2-PM-FINAL | Penetration testing report | LaTeX report prepared | [Final report folder](W2-PM-FINAL/) |

## Skills practiced

- WHOIS domain registration lookup
- Web technology fingerprinting with WhatWeb
- DNS resolution and record enumeration
- HTTP response header inspection
- Web Application Firewall fingerprinting
- Network identification with `ipconfig`
- Host discovery with Zenmap / Nmap
- Topology visualization, evidence collection and reporting

## Repository structure

```text
NETWORKWALKS-TAHA-B084-WK2-CYBERSECURITY/
├── README.md
├── W2-PM1/
│   ├── README.md
│   └── images/
│       ├── task1_pm1.png
│       ├── task2_pm1.png
│       ├── task3_pm1.png
│       ├── task4_pm1.png
│       ├── task5_pm1.png
│       └── task6_pm1.png
├── W2-PM5/
│   ├── README.md
│   └── images/
│       ├── task1_pm2.png
│       ├── task2_pm2.png
│       ├── task3_pm2.png
│       └── task7_pm2.png
└── W2-PM-FINAL/
    └── README.md
```

> Screenshot files shown above are **expected filenames**, not included in this starter package. Add your own redacted screenshots to the appropriate `images/` folders.

## Main outcomes

**PM1:** Identified GoDaddy domain registration, HostGator DNS, Apache / WordPress website fingerprints, DNS and email records, and a WAF fingerprint consistent with ModSecurity.

**PM5:** Completed a host-discovery scan on an authorized local `/24` network: **256 addresses scanned, 3 hosts reported up, 3.30 seconds elapsed**. Exported a Zenmap topology PDF.

## Privacy and ethical use

- Publicly shared IPv4 addresses are partially masked, e.g. `192.168.100.X`.
- MAC addresses are half-masked, e.g. `04:56:E5:XX:XX:XX`.
- **Redact the screenshot pixels themselves** before uploading. Markdown masking does not hide information embedded in PNGs.
- Public IP addresses, DNS records, and hostnames may be visible in the original tool output; review all screenshots for identifiers and session cookies.
- The sample authorization letter supplied with training materials is **not** an authorization letter issued to me. Only scan systems and networks you own or have explicit permission to assess.

## References

- [Nmap / Zenmap](https://nmap.org/)
- [Kali Linux](https://www.kali.org/)
- [NetworkWalks](https://networkwalks.com/)

---
*Prepared by Taha Chebil — NetworkWalks Internship, Batch B084 (November 2026).*
