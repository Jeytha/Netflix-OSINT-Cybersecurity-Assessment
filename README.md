# Open-Source Intelligence (OSINT)-based cybersecurity risk assessment of Netflix, Inc.

## 📘 Overview

This project presents an Open-Source Intelligence (OSINT)-based cybersecurity risk assessment of Netflix, Inc.
It examines publicly available data to identify cloud dependencies, exposed assets, and potential vulnerabilities.

## 🔍 Summary

### Cloud Provider: AWS

### Architecture: 

Microservices, containers (Titus/Docker), distributed systems (Kafka, Cassandra, Spark)

### Risks:

Subdomain sprawl

Weak DMARC policy (p=none)

Cloud misconfigurations

Vulnerable open-source components (e.g., Genie CVE-2024-4701)

Credential stuffing & API abuse

## ⚙️ Methodology

Only passive OSINT tools were used:

DNS & MX lookups

Public CVE and vulnerability databases

Company tech blogs and advisories

Security news and reports

No intrusive or active scanning was performed.

## 🧩 Key Findings

Cloud-first design increases configuration risk.

Open-source exposure (e.g., Genie framework).

Email security gaps (DMARC p=none).

Large attack surface from numerous subdomains.

Common threats: credential stuffing, API abuse, DDoS, and phishing.

## 🛠️ Recommendations

Tighten cloud permissions and IAM roles.

Enforce phishing-resistant MFA.

Strengthen email authentication (DMARC p=reject).

Use API gateways with rate limits.

Continuously scan open-source dependencies.

## ⚠️ Disclaimer

This project uses publicly available information only for academic and defensive purposes.
No intrusive or illegal activity was performed.
