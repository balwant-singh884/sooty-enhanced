<p align="center">
  <img src="sooty%20enhanced.png" width="500">
</p>

<h1 align="center">Sooty Enhanced</h1>

<p align="center">
Modern SOC Analyst & Threat Intelligence Toolkit
</p>
<p align="center">

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-GPLv3-green)

</p>
A modern SOC Analyst and Threat Intelligence Toolkit designed to accelerate IOC investigation, threat hunting, incident response, and security operations workflows.

---

## Overview

Sooty Enhanced is an actively maintained and enhanced fork of the original Sooty project. The goal of this project is to evolve Sooty into a modern SOC Analyst platform capable of performing IOC investigation, threat intelligence enrichment, reputation analysis, incident response support, and security operations automation from a single interface.

This project is currently under active development with new features being added regularly.

---

## Key Features

### IOC Investigation

- IOC Classification Engine
- IPv4 Detection
- IPv6 Detection
- Domain Detection
- URL Detection
- Email Detection
- MD5 Detection
- SHA1 Detection
- SHA256 Detection

### Threat Intelligence

- Reverse DNS Lookup
- Reputation Analysis
- DNS Investigation
- WHOIS Analysis
- Threat Enrichment

### Security Operations

- URL Analysis
- Email Analysis
- Hash Analysis
- IOC Enrichment
- Incident Response Support

---

## Current Capabilities

### URL Utilities

- URL Sanitization
- URL Decoding
- URL Unshortening
- SafeLink Decoding
- ProofPoint Decoding
- Unfurl URL Analysis

### DNS & Network Analysis

- Reverse DNS Lookup
- DNS Lookup
- WHOIS Lookup

### Reputation Analysis

- VirusTotal Checks
- AbuseIPDB Checks
- BadIPs Checks
- TOR Exit Node Detection
- URLScan Integration

### Email Security

- Email Header Analysis
- Email Address Reputation Analysis
- Phishing Investigation
- HaveIBeenPwned Checks

### Hash Analysis

- File Hash Generation
- Hash Verification
- Threat Intelligence Lookup

---

## Enhancements Added

### Version 2.0 Enhancements

- IOC Investigator Module
- IOC Classification Engine
- Reverse DNS Lookup
- Python 3.13 Compatibility Improvements
- Dependency Modernization
- Enhanced Development Workflow
- GitHub Development Branch Structure

---

## Screenshots

### Main Menu

*Screenshot Coming Soon*

### IOC Investigator

*Screenshot Coming Soon*

### Reverse DNS Lookup

*Screenshot Coming Soon*

### Threat Intelligence Dashboard

*Planned Feature*

---

## Installation

### Kali Linux / Ubuntu

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

Launch the application:

```bash
python3 Sooty.py
```

---

## Docker

```bash
docker build -t sooty-enhanced .
docker run --rm -it sooty-enhanced
```

---

## Usage Example

IOC Investigation:

```text
IOC: 8.8.8.8
IOC Type: IPv4
Reverse DNS: dns.google
```

---

## Roadmap

### Completed

- IOC Classification Engine
- Reverse DNS Lookup
- Dependency Modernization
- Python 3.13 Compatibility Updates

### In Progress

- ASN Lookup
- Organization Lookup
- Country Lookup

### Planned

- VirusTotal Integration Improvements
- AbuseIPDB Integration Improvements
- AlienVault OTX Integration
- PDF Report Generation
- IOC Correlation Engine
- Threat Intelligence Dashboard
- Case Management System
- Reporting Engine

---

## Project Vision

The long-term goal of Sooty Enhanced is to become a unified SOC Analyst toolkit that combines:

- IOC Investigation
- Threat Intelligence
- Incident Response
- Threat Hunting
- Security Operations Automation
- Reporting & Case Management

within a single platform.

---

## Modernization Progress

Sooty Enhanced is undergoing a complete modernization effort to transform the original project into a modern SOC Analyst and Threat Intelligence platform.

### Completed

- IOC Investigator Module
- IOC Classification Engine
- Reverse DNS Lookup
- Python 3.13 Compatibility Improvements
- Dependency Modernization
- Updated Project Documentation
- Enhanced Git Development Workflow
- Custom Project Branding

### In Progress

- ASN Lookup
- Organization Lookup
- Country Lookup
- Improved IOC Enrichment

### Planned

- VirusTotal Integration
- AbuseIPDB Integration
- AlienVault OTX Integration
- IOC Correlation Engine
- PDF Report Generation
- Threat Intelligence Dashboard
- Reporting Engine
- Case Management System

### Long-Term Vision

Build a unified platform for:

- IOC Investigation
- Threat Intelligence
- Threat Hunting
- Incident Response
- Security Operations
- Security Reporting
- SOC Workflow Automation
## Maintainer

### Balwant Singh

Cybersecurity Student  
SOC Analyst Enthusiast  
Poornima University

GitHub:
https://github.com/balwant-singh884

---

## Acknowledgements

Sooty Enhanced is based on the original open-source Sooty project. This fork extends and modernizes the project while preserving the spirit of the original tool.

---

## License

GPL v3
