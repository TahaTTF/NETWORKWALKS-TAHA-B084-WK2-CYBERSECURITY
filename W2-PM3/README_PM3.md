# W2-PM3 — Footprinting with Maltego

**Program:** NetworkWalks Cybersecurity & Ethical Hacking Internship  
**Batch:** B084  
**Participant:** Taha Chebil  
**Status:** Completed

## Objective

Use Maltego to visualize relationships between public entities and perform basic, permission-based reconnaissance on `networkwalks.com`.

## Task 1 — Install and configure Maltego

- Installed and launched **Maltego Graph (Desktop) 4.14.0** on Windows.
- Opened a new investigation graph and used the **Normal** privacy mode.

## Task 2 — Find an organization email address

1. Added a **Domain** entity and set it to `networkwalks.com`.
2. Ran an email-related transform: **To Email Addresses [Search Engine]**.
3. Observed one returned email entity: `info@networkwalks.com`.
4. Verified the result visually as a connection between the domain and the email address in the graph.

**Evidence:** `img1.png` — domain-to-email relationship.

## Additional exploration — Person and related websites

- Added a **Person** entity named `Waqas Karim CCIE`.
- Explored a graph showing multiple associated website entities, including social platforms and professional sites.
- This graph demonstrates entity relationships, **not independently verified ownership or identity**. Associations from transforms should be checked before being treated as facts.

**Evidence:** `img2.png` — person-to-websites graph.

## Lessons learned

- **Entity:** A node representing a domain, person, email, website, etc.
- **Transform:** A query or operation that finds and links related information.
- **Graph:** A visual map of entities and their relationships.
- **OSINT validation:** A suggested link is a lead, not proof of a relationship.
- **Privacy and scope:** Limit investigations to authorized targets and public data.

## Evidence folder

```text
images/
└── PM3/
    ├── img1.png
    └── img2.png
```

## Conclusion

Maltego helped organize reconnaissance results visually. The main domain investigation returned a public contact email, and the additional person graph demonstrated how relationship mapping works.

**Reference:** NetworkWalks, *W2-PM3 — Footprinting with Maltego*, Tasks 1–2.
