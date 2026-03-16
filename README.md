# Inter IIT Tech Meet 11.0 - Cybersecurity Solutions 🥇

This repository contains the Gold Medal-winning solutions for the **Cybersecurity Problem Statement: "Sneaking into the Cyber-Cracks"** at the Inter IIT Tech Meet 11.0, held at IIT Kanpur.

Developed by the team from **[Insert Your IIT Name]**, these solutions demonstrate advanced skills in web application security, exploit development, and technical reporting.

## 🌟 Achievement: GOLD MEDAL
The competition challenged teams to develop Proof-of-Concept (PoC) exploits for real-world high-severity vulnerabilities (CVEs) in web-based applications. Our team successfully analyzed, reproduced, and documented 5 major vulnerabilities, securing the top spot.

---

## 📂 Project Overview
The problem statement from **Saptang Labs** required participants to:
1. Understand target web applications and deployment techniques.
2. Identify and analyze critical attack surfaces.
3. Develop professional Proof-of-Concept exploits.
4. Document the entire process with technical reports and video demonstrations.

---

## 🛡️ Vulnerabilities Addressed

| CVE ID | Vulnerability Type | Target Software | Impact |
| :--- | :--- | :--- | :--- |
| **[CVE-2022-31626](./Vulnerabilities/CVE-2022-31626)** | Buffer Overflow (PHP) | PHP pdo_mysql | Remote Code Execution |
| **[CVE-2022-44118](./Vulnerabilities/CVE-2022-44118)** | RCE via .phar | DedeCMSV6 | Full System Compromise |
| **[CVE-2022-32996](./Vulnerabilities/CVE-2022-32996)** | Backdoor | django-navbar-client | Sensitive Data Theft |
| **[CVE-2022-30524](./Vulnerabilities/CVE-2022-30524)** | Memory Access Crash | Xpdf | Denial of Service |
| **[CVE-2022-31103](./Vulnerabilities/CVE-2022-31103)** | DOM-based DoS | lettersanitizer | Application Unresponsive |

---

## 📽️ Demonstrations
Each vulnerability folder contains:
- **`README.md`**: A detailed technical breakdown of the vulnerability and exploit.
- **`report.pdf`**: The official technical report submitted during the competition.
- **`demo.mkv`**: A high-definition video demonstration of the exploit in action.

---

## 🛠️ Tools & Technologies
- **Languages**: Python (Exploit development), PHP, JavaScript, C++
- **Security Tools**: GDB, Burp Suite, Netcat, Rogue MySQL Server
- **Infrastructure**: Apache2, PHP-FPM, MySQL

---

## 👨‍💻 The Team
*Documentation for the Inter IIT Tech Meet 11.0 Gold-winning contingent.*

---
*Disclaimer: This repository is for educational and ethical security research purposes only. All exploits were developed in controlled, authorized environments.*
