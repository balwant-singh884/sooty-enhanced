<p align="center">
  <img src="sooty enhanced.png" width="700">
</p>

<h1 align="center">Sooty Enhanced</h1>

<p align="center">
SOC Analyst • Threat Intelligence • IOC Investigation Toolkit
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Platform](https://img.shields.io/badge/Platform-Kali%20Linux%20%7C%20Ubuntu-orange)
![Version](https://img.shields.io/badge/Version-1.4.0-red)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-GPLv3-green)

</p>

---

# 🚀 About

Sooty Enhanced is a modernized SOC Analyst and Threat Intelligence toolkit designed to help cybersecurity professionals, blue teams, incident responders, and students perform rapid IOC investigation, threat enrichment, reputation analysis, phishing investigations, DNS intelligence, and security operations tasks from a single command-line interface.

Built upon the original open-source **Sooty** project, this enhanced version introduces new intelligence capabilities, bug fixes, modern compatibility improvements, and additional investigation workflows aimed at improving analyst efficiency.

Whether you are investigating suspicious IP addresses, domains, URLs, email addresses, or file hashes, Sooty Enhanced provides a lightweight platform for performing common SOC and Threat Intelligence operations.

---

# ✨ Features

| Module | Capabilities |
|----------|-------------|
| 🔍 IOC Investigator | IOC Classification, ASN Lookup, Organization Intelligence, Country Intelligence |
| 🌐 DNS Toolkit | DNS Lookup, Reverse DNS Lookup, WHOIS Analysis |
| 🛡️ Reputation Checker | VirusTotal, AbuseIPDB, BadIPs, TOR Exit Node Detection |
| 📧 Email Security | Email Reputation Analysis, HIBP Checks, Phishing Investigation |
| 🔗 URL Analysis | URLScan Integration, URL Decoding, URL Sanitization |
| 🔐 Hash Analysis | MD5, SHA1, SHA256 Generation & Threat Intelligence Lookup |
| 📊 Threat Intelligence | IOC Enrichment & Investigation Workflows |
| ⚙️ SOC Operations | Investigation Support & Threat Hunting Assistance |

---

# 🆕 What's New in v1.4.0

## Added

- IOC Investigator Module
- IOC Classification Engine
- ASN Intelligence Lookup
- Organization Intelligence Lookup
- Country Intelligence Lookup
- Reverse DNS Integration
- Improved IOC Enrichment

## Improved

- Domain Reputation Analysis
- URL Processing Logic
- Error Handling
- Linux Compatibility
- Python 3.13 Support
- Investigation Workflow

## Fixed

- Proofpoint Decoder Issues
- URLScan Integration Problems
- Domain Resolution Bugs
- Reputation Checker Bugs
- Multiple Navigation Issues
- Output Handling Improvements

---

# 📸 Screenshots

## Main Menu

![Main Menu](readmeimages/main-menu.png)

> 📸 INSERT MAIN MENU SCREENSHOT HERE

---

## IOC Investigator

![IOC Investigator](readmeimages/ioc-investigator.png)

> 📸 INSERT IOC INVESTIGATOR SCREENSHOT HERE

---

## Reputation Checker

![Reputation Checker](readmeimages/reputation-checker.png)

> 📸 INSERT REPUTATION CHECKER SCREENSHOT HERE

---

## DNS Toolkit

![DNS Toolkit](readmeimages/dns-toolkit.png)

> 📸 INSERT DNS TOOLKIT SCREENSHOT HERE

---

## URLScan Analysis

![URLScan Analysis](readmeimages/urlscan-analysis.png)

> 📸 INSERT URLSCAN SCREENSHOT HERE

---

## Hash Analysis

![Hash Analysis](readmeimages/hash-analysis.png)

> 📸 INSERT HASH ANALYSIS SCREENSHOT HERE

---

# 🔎 IOC Investigation Example

### Input

```text
8.8.8.8
```

### Output

```text
========================================
      IOC INTELLIGENCE SUMMARY
========================================

IOC           : 8.8.8.8
Type          : IPv4
Reverse DNS   : dns.google
ASN           : 15169
Organization  : GOOGLE - Google LLC
Country       : US

========================================
```

---

# 🛠️ Installation

## Kali Linux / Ubuntu

Clone the repository:

```bash
git clone https://github.com/balwant-singh884/sooty-enhanced.git
cd sooty-enhanced
```

Create a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python3 Sooty.py
```

---

# ⚙️ Configuration

Copy the example configuration:

```bash
cp example_config.yaml config.yaml
```

Edit the configuration file and add your API keys.

Supported services:

- VirusTotal
- AbuseIPDB
- URLScan
- HaveIBeenPwned
- EmailRep (Optional)

Example:

```yaml
VT_API_KEY: YOUR_KEY_HERE
ABUSEIPDB_API_KEY: YOUR_KEY_HERE
URLSCAN_API_KEY: YOUR_KEY_HERE
HIBP_API_KEY: YOUR_KEY_HERE
EMAILREP_API_KEY: YOUR_KEY_HERE
```

---

# 🐳 Docker

Build image:

```bash
docker build -t sooty-enhanced .
```

Run container:

```bash
docker run --rm -it sooty-enhanced
```

---

# 📂 Project Structure

```text
Sooty/
│
├── Modules/
│   ├── Reputation
│   ├── URLScan
│   ├── DNS
│   ├── Decoders
│   └── Intelligence Modules
│
├── config/
├── readmeimages/
├── output/
│
├── Dockerfile
├── LICENSE
├── README.md
├── requirements.txt
├── example_config.yaml
└── Sooty.py
```

---

# 🎯 Current Capabilities

### IOC Investigation

- IPv4 Detection
- IPv6 Detection
- Domain Detection
- URL Detection
- Email Detection
- MD5 Detection
- SHA1 Detection
- SHA256 Detection

### Threat Intelligence

- ASN Lookup
- Organization Intelligence
- Country Intelligence
- Reverse DNS Analysis
- Domain Intelligence

### Reputation Analysis

- VirusTotal
- AbuseIPDB
- BadIPs
- TOR Exit Nodes
- URLScan

### Security Operations

- IOC Investigation
- Threat Hunting Support
- Incident Response Support
- Reputation Analysis
- Threat Intelligence Enrichment

---

# 🗺️ Roadmap

## Completed ✅

- IOC Investigator
- IOC Classification Engine
- ASN Intelligence
- Organization Intelligence
- Country Intelligence
- Reverse DNS Lookup
- URLScan Integration
- DNS Toolkit
- Reputation Checker Enhancements
- Python 3.13 Compatibility
- Linux Compatibility Improvements

## Planned 🚧

- AlienVault OTX Integration
- Threat Feed Aggregation
- IOC Correlation Engine
- PDF Report Generation
- Enhanced Threat Intelligence Workflows
- Multi-Source Intelligence Correlation
- Investigation Reporting Improvements

---

# 🎓 Use Cases

Sooty Enhanced can be used for:

- SOC Analyst Investigations
- Incident Response
- IOC Validation
- Threat Hunting
- Threat Intelligence Enrichment
- Phishing Investigations
- Malware Investigations
- Security Research
- Cybersecurity Learning & Training

---

# 👨‍💻 Maintainer

## Balwant Singh

Cybersecurity Student  
SOC Analyst Aspirant  
Poornima University, Jaipur

### Connect

GitHub:

https://github.com/balwant-singh884

---

# 🙏 Acknowledgements

Sooty Enhanced is based on the original open-source **Sooty** project created by **TheresAFewConors**.

This project extends the original tool with:

- IOC Investigation Features
- ASN Intelligence
- Threat Enrichment
- Improved Compatibility
- Enhanced Investigation Workflows
- Modernized Documentation
- Ongoing Feature Development

Special thanks to all contributors of the original Sooty project and the open-source cybersecurity community.

---

# 📜 License

Licensed under the **GNU General Public License v3.0 (GPLv3)**.

See the LICENSE file for full details.

---

<p align="center">
Built with ❤️ for SOC Analysts, Threat Hunters, Incident Responders, and Cybersecurity Students.
</p>
