# Inter IIT Tech Meet 11.0 — Cybersecurity PS Solution

**Gold Medal winning solution | Sneaking into the Cyber-Cracks | Saptang Labs**

---

## About

This repository contains the **Gold Medal-winning** solutions for the cybersecurity problem statement *"Sneaking into the Cyber-Cracks"* at **Inter IIT Tech Meet 11.0**, held at IIT Kanpur.
Developed by the team from **IIT Indore**, these solutions demonstrate advanced skills in web application security, exploit development, and technical reporting.

The challenge, presented by **Saptang Labs**, required participating teams to develop professional Proof-of-Concept (PoC) exploits for real-world, high-severity CVEs in web-based applications. Our team successfully analyzed, reproduced, and documented **5 vulnerabilities** spanning buffer overflows, supply-chain backdoors, remote code execution, and denial-of-service attacks securing the top spot.

---

## Problem Statement

Participants were evaluated on their ability to:

1. Understand target web applications and their deployment architecture.
2. Identify and analyze critical attack surfaces within each application.
3. Develop working Proof-of-Concept exploits demonstrating each vulnerability.
4. Document the full exploitation process through technical reports and video demonstrations.
5. Adhere to ethical standards and best practices throughout the exploit development lifecycle.

> The original problem statement is available at [`Problem_Statement.pdf`](./Problem_Statement.pdf).

---

## Vulnerabilities

| CVE ID | Vulnerability Type | Target Software | Severity | Impact |
|:---|:---|:---|:---|:---|
| [CVE-2022-31626](./Vulnerabilities/CVE-2022-31626) | Buffer Overflow | PHP `pdo_mysql` / `mysqlnd` | HIGH (8.8) | Remote Code Execution |
| [CVE-2022-44118](./Vulnerabilities/CVE-2022-44118) | Incomplete Blacklist Bypass | DedeCMS v6.1.9 | CRITICAL (9.8) | Full system compromise|
| [CVE-2022-32996](./Vulnerabilities/CVE-2022-32996) | Supply-Chain Backdoor | `django-navbar-client` | CRITICAL (9.8) | Sensitive data theft |
| [CVE-2022-30524](./Vulnerabilities/CVE-2022-30524) | Invalid Memory Access | Xpdf 4.0.4 (`pdftotext`) | HIGH (7.8) | Denial of Service |
| [CVE-2022-31103](./Vulnerabilities/CVE-2022-31103) | DOM-based DoS | `lettersanitizer` / `react-letter` | HIGH (7.5) | Application unresponsive |

---

## Repository Structure

```
.
├── README.md                       # This file
├── Problem_Statement.pdf           # Original problem statement from Saptang Labs
└── Vulnerabilities/
    ├── CVE-2022-30524/
    │   ├── README.md               # Technical analysis
    │   ├── report.pdf              # Submitted report
    │   └── demo.mkv                # Video demonstration
    ├── CVE-2022-31103/
    │   ├── README.md
    │   ├── report.pdf
    │   └── demo.mkv
    ├── CVE-2022-31626/
    │   ├── README.md
    │   ├── report.pdf
    │   └── demo.mkv
    ├── CVE-2022-32996/
    │   ├── README.md
    │   ├── report.pdf
    │   └── demo.mkv
    └── CVE-2022-44118/
        ├── README.md
        ├── report.pdf
        └── demo.mkv
```

Each vulnerability directory contains:

- **`README.md`** — Detailed technical breakdown of the vulnerability, root cause analysis, and exploitation methodology.
- **`report.pdf`** — The official technical report submitted during the competition.
- **`demo.mkv`** — Video demonstration of the exploit in a controlled environment.

---

## Tools and Technologies

| Category | Tools |
|:---|:---|
| Languages | Python, PHP, JavaScript, C++ |
| Security Tools | GDB, Burp Suite, Netcat, Rogue MySQL Server |
| Infrastructure | Apache2, PHP-FPM, MySQL, PyPI Server |
| Analysis | Static code review, heap analysis, protocol inspection |

---

## Disclaimer

This repository is published for **educational and ethical security research purposes only**. All exploits were developed and demonstrated in controlled, authorized environments as part of an academic competition.

---

*Inter IIT Tech Meet 11.0 — Gold Medal winning solution by team from IIT Indore*
