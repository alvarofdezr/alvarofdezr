# Álvaro Fernández Ramos

Computer Engineering @ University of Seville   
Focused on cybersecurity engineering, systems programming, and secure software design.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/álvaro-fernández-71b25a404)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:alvarofdezram@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/alvarofdezr)

## About

I build security-focused software with emphasis on endpoint telemetry, encrypted systems, and offensive security tooling. My work focuses on understanding how attacks work at the system level, then building resilient architectures to detect and respond to them.

**Current interests:**
- Endpoint detection and response (EDR) architecture
- Reverse engineering & malware analysis
- Secure systems design and cryptographic engineering
- Concurrent networking tools and high-performance systems

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

## Featured Projects

### [Aegis Sentinel](https://github.com/alvarofdezr/Aegis-sentinel) — Endpoint Detection & Response

Experimental endpoint detection and response system focused on host telemetry collection and detection pipelines.

- Agent-server architecture over HTTPS for telemetry ingestion
- Collection of process, network, filesystem, and USB events
- YARA-based detection engine with optional threat intelligence integration
- Automated response actions (process termination, isolation simulation)
- Web dashboard with role-based access control (RBAC)
- Containerized deployment using Docker

**Engineering focus:** system architecture, telemetry design, detection logic, and observability (structured logging and metrics)

---

### [Harpocrates](https://github.com/alvarofdezr/Harpocrates) — Encrypted Password Vault

Secure local password storage system designed to explore applied cryptography and vault design.

- AES-256-GCM authenticated encryption
- Argon2id key derivation
- Dual-factor access model (password + secret key)
- Tamper-evident audit log design using HMAC
- Integration with HaveIBeenPwned (k-anonymity model)
- CI pipeline with security checks (Bandit)

**Focus:** applied cryptography, secure storage design, and key management trade-offs

---

### [Ares](https://github.com/alvarofdezr/Ares) — Concurrent Network Reconnaissance
**High-performance reconnaissance toolkit in Go**

- Concurrent port scanning with tunable worker pools
- Vulnerability discovery and service enumeration
- Efficient network I/O with goroutine patterns
- Useful for penetration testing and network reconnaissance

**Architecture:** Worker pool pattern, context cancellation, backpressure handling.

---

### [Basilisk](https://github.com/alvarofdezr/Basilisk) — EDR Prototype System

Prototype endpoint detection and response system that served as the base architecture for Aegis Sentinel.

- Host telemetry collection (process, network, filesystem)
- YARA-based scanning integration
- Basic response actions
- REST API backend (FastAPI)
- Web dashboard for event visualization

**Status:** Experimental system; superseded by Aegis Sentinel


## Learning & Development

**Active areas:**
- Advanced Go: concurrency patterns, networking, performance optimization
- Linux internals: syscall tracing, eBPF, process memory forensics
- Malware analysis and reverse engineering
- Cryptographic engineering and protocol design

## Contact

Open to internships, junior positions, and security research collaborations.
