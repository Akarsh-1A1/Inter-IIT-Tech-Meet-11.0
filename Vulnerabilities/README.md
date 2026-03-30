# Vulnerabilities

This directory contains the complete analysis, Proof-of-Concept exploits, technical reports, and video demonstrations for each CVE addressed during the competition.

---

## Index

| CVE ID | Severity | Type | Target |
|:---|:---|:---|:---|
| [CVE-2022-31626](./CVE-2022-31626) | HIGH (8.8) | Heap Buffer Overflow | PHP `pdo_mysql` / `mysqlnd` |
| [CVE-2022-44118](./CVE-2022-44118) | CRITICAL (9.8) | Incomplete Blacklist Bypass | DedeCMS V6 |
| [CVE-2022-32996](./CVE-2022-32996) | CRITICAL (9.8) | Supply-Chain Backdoor | `django-navbar-client` |
| [CVE-2022-30524](./CVE-2022-30524) | HIGH (7.8) | Invalid Memory Access | Xpdf 4.0.4 |
| [CVE-2022-31103](./CVE-2022-31103) | HIGH (7.5) | DOM-based DoS | `lettersanitizer` |

---

## Directory Structure

Each vulnerability directory follows a consistent structure:

```
CVE-YYYY-NNNNN/
├── README.md       # Technical analysis and exploitation methodology
├── report.pdf      # Official competition submission report
└── demo.mkv        # Video demonstration of the exploit
```
