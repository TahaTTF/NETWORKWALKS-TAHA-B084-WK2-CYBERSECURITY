
# NetworkWalks — Week 2 Cybersecurity Internship

**Intern:** Taha Chebil  
**Batch:** B084  
**Program:** Cybersecurity & Ethical Hacking  
**Week:** 2 — Footprinting, Reconnaissance & Network Scanning  
**Status:** W2-PM1, W2-PM2, W2-PM3 and W2-PM5 completed; final report prepared.

## Completed modules

| Module | Focus | Outcome | Documentation |
|---|---|---|---|
| W2-PM1 | Footprinting with six Kali Linux tools | 6/6 tasks completed | [PM1 notes](W2-PM1/README.md) |
| W2-PM2 | Google Hacking Database (GHDB) and Google Dorking | 2/2 tasks completed: 10 camera findings and 10 mathematics PDF listings | [PM2 notes](W2-PM2/README.md) |
| W2-PM3 | Footprinting with Maltego | 2/2 tasks completed: installation and email reconnaissance | [PM3 notes](W2-PM3/README.md) |
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
- Google Hacking Database (GHDB) and advanced Google search operators
- Google Dorking for publicly indexed resources
- Identification of publicly accessible camera interfaces
- Discovery of mathematics PDF documents and directory listings
- OSINT (Open-Source Intelligence) techniques
- Maltego installation and configuration on Windows
- Domain and email reconnaissance using Maltego transforms
- Visualization of relationships between domains, email addresses, people and websites

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
├── W2-PM2/
│   ├── README_PM2.md
│   └── W2-PM2_GHDB_TASKS_Report.pdf
├── W2-PM3/
│   ├── README_PM3.md
│   └── images/
│       ├── img1.png
│       └── img2.png
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

## Main outcomes

**PM1:** Identified GoDaddy domain registration, HostGator DNS, Apache / WordPress website fingerprints, DNS and email records, and a WAF fingerprint consistent with ModSecurity.

**PM2:** Practiced Google Dorking and open-source reconnaissance. Documented 10 publicly reachable camera-related findings and 10 mathematics PDF listings using Google search operators and public sources. Learned about search engine indexing, directory listing, information exposure and responsible OSINT practices. Public accessibility alone does not establish a vulnerability.

**PM3:** Installed and configured Maltego Graph Desktop 4.14.0 on Windows. Created a domain entity for `networkwalks.com` and executed an email-related transform, identifying the publicly associated address `info@networkwalks.com`. Additionally explored person-to-website relationships using Maltego's graphical visualization capabilities.

**PM5:** Completed a host-discovery scan on an authorized local `/24` network: **256 addresses scanned, 3 hosts reported up, 3.30 seconds elapsed**. Exported a Zenmap topology PDF.

## Privacy and ethical use

- Publicly shared IPv4 addresses are partially masked, e.g. `192.168.X.X`.
- MAC addresses are half-masked, e.g. `04:X:X:XX:XX:XX`.
- **Redact the screenshot pixels themselves** before uploading. Markdown masking does not hide information embedded in PNGs.
- Public IP addresses, DNS records, and hostnames may be visible in the original tool output; review all screenshots for identifiers and session cookies.
- Camera-related findings are documented for educational purposes. Direct camera endpoints, private surveillance feeds and authentication details should not be republished without authorization.
- Google Dorking and Maltego reconnaissance were performed for educational OSINT practice. Public availability does not automatically imply permission to access or redistribute information.
- The sample authorization letter supplied with training materials is **not** an authorization letter issued to me. Only scan systems and networks you own or have explicit permission to assess.

## References

- [Nmap / Zenmap](https://nmap.org/)
- [Kali Linux](https://www.kali.org/)
- [NetworkWalks](https://networkwalks.com/)
- [Google Hacking Database — Exploit Database](https://www.exploit-db.com/google-hacking-database)
- [Maltego](https://www.maltego.com/)

---
*Prepared by Taha Chebil — NetworkWalks Internship, Batch B084 (November 2026).*
