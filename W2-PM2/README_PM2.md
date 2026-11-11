# W2-PM2 — Google Hacking Database (GHDB)

**Program:** NetworkWalks Cybersecurity & Ethical Hacking Internship  
**Batch:** B084  
**Participant:** Taha Chebil  
**Status:** Completed (discovery exercises)

## Objective

Learn how advanced search operators (Google dorks) can discover publicly indexed information, including camera webpages and mathematics PDF documents. Practice distinguishing *publicly accessible* information from *authorized* access and identifying possible information exposure without attempting exploitation.

## Task 1 — Public camera discovery

- Recorded 10 camera-related findings during the exercise, using a combination of public camera directories, GitHub references, and Google search operators.
- Example searches:
  - `site:skylinewebcams.com "live webcam"`
  - `intitle:"webcamXP" inurl:8080`
- Some results were intentionally published public webcams; others had unclear ownership or access permissions. **Public visibility alone does not establish a security vulnerability.**
- No credentials were used or collected. Do not publish direct IP-camera URLs or screenshots of private interiors in a public repository without permission.

## Task 2 — Mathematics PDF discovery

Recorded 10 PDF listings using:

```text
intitle:index.of "parent directory" mathematics pdf
site:mit.edu filetype:pdf mathematics
site:edu filetype:pdf "probability theory" lecture notes
```

| # | Document / description | Source |
|---|---|---|
| 1 | A Computational Introduction to Number Theory and Algebra (Version 2) | ochicken.net |
| 2 | Advanced Modern Algebra, Part 1 | ochicken.net |
| 3 | Polynomial Algorithms in Computer Algebra | ochicken.net |
| 4 | Statistical Inference | ochicken.net |
| 5 | Mathematics for Computer Science (2015) | MIT OpenCourseWare |
| 6 | Mathematics for Computer Science (2018) | MIT CSAIL |
| 7 | Mathematics course notes | Cornell University |
| 8 | Probability course notes | Stanford University |
| 9 | Mathematics course notes | Harvard University |
| 10 | Mathematics lecture notes | UC Davis |

**Note:** These are ten PDF listings, not necessarily ten unique ebooks. The two MIT PDFs are editions of the same work. Third-party PDF redistribution rights were not verified; this repository does not mirror the files.

## Lessons learned

- **OSINT:** Collecting and analyzing publicly available information.
- **Search operators:** `site:`, `filetype:`, `intitle:`, `inurl:` and quoted phrases narrow search results.
- **Directory listing:** An exposed index may be intentional or a server configuration issue; verify context before claiming a vulnerability.
- **Responsible reporting:** Avoid publishing camera endpoints, credentials, private scenes, or unlicensed PDFs.

## Challenge

The Exploit-DB GHDB webpage returned an HTTP 502 origin-server timeout during the exercise. Alternative public search queries were used to complete the learning objectives.

## Evidence

Save sanitized screenshots in `images/PM2/`. Remove identifiable individuals, private camera addresses, credentials, and sensitive location details before publishing.

## Conclusion

This module demonstrated how search-engine indexing can reveal resources and why organizations should review publicly exposed content and access controls.
