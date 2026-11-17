<div align="center">
  <h2>Álvaro Fernández Ramos</h2>
  <p><b>Security Engineer & Systems Developer</b></p>
  <p>Focusing on Host Telemetry, Offensive Tooling Architecture, Systems Engineering & Applied Cryptography</p>

  <a href="https://alvarofdezr.github.io">🌐 Website</a> •
  <a href="https://www.linkedin.com/in/%C3%A1lvaro-fern%C3%A1ndez-71b25a404">💼 LinkedIn</a> •
  <a href="mailto:alvarofdezram@gmail.com">📫 Email</a>
</div>

<br>

### Technical Profile

| Domain | Technologies & Methodologies |
| :--- | :--- |
| **Languages** | `Go` · `Python` · `C` · `Bash` · `JavaScript` · `x86-64 ASM` |
| **Defensive Security** | EDR Sensor Architecture, Telemetry Ingestion, YARA Engine, Zero-Trust |
| **Offensive Tooling** | Concurrent Network Scanners, In-Memory Evasion, Syscall Injection |
| **Applied Cryptography** | AES-256-GCM, Argon2id, HKDF, HMAC, Double Ratchet (E2EE) |
| **Systems & Verification** | Linux Internals, File Format Parsers, Z3 SMT Solver, Docker, CI/CD |

---

### Key Projects

#### [Aegis Sentinel](https://github.com/alvarofdezr/Aegis-sentinel) — Endpoint Detection & Response (EDR)
* Built in **Go** to capture live host processes, network telemetry, and system events.
* Integrates an internal **YARA engine** for real-time memory and artifact signature scanning.
* Exposes a modular REST API for automated security orchestration, alerting, and triage.

#### [Ares](https://github.com/alvarofdezr/Ares) — High-Performance Network Scanner
* Concurrent network recon framework built with Go's `sync` primitives, channels, and worker pools.
* Employs non-blocking network I/O for ultra-fast port identification and banner grabbing.

#### [ARQMED Studio](https://github.com/alvarofdezr/Arqmed) — Bidirectional FIEBDC-3 (.BC3) Engine & Web Editor
* Zero-runtime-dependency **Python** parsing engine supporting legacy encodings (`CP850`, `Windows-1252`, `UTF-8`) and relational tree resolution.
* Exporters to SQLite, JSON, and CSV with graph cascade recalculation algorithms for unit-price variations.
* Standalone client-side web editor with `IndexedDB` persistence and Android tablet support.

#### [Harpocrates](https://github.com/alvarofdezr/Harpocrates) — Zero-Trust Password Vault
* Standalone credential manager utilizing **AES-256-GCM** for confidentiality and authenticated integrity.
* Leverages **Argon2id** for brute-force resistant key derivation and **HMAC** for tamper-evident audit trails.

#### [SecureChain SSC](https://github.com/alvarofdezr/securechain-ssc-ingestion) — Supply Chain Verification (BSc Thesis)
* Software supply-chain security analyzer targeting Go modules and package ecosystems.
* Generates CycloneDX SBOMs and performs formal dependency conflict proofs via the **Z3 Theorem Prover**.

<details>
<summary><b>Other Projects & Research Prototypes</b></summary>
<br>

* **[Cript](https://github.com/alvarofdezr/cript)** `Python`: End-to-End Encrypted (E2EE) framework simulating the Double Ratchet protocol and HKDF key derivation trees.
* **[Basilisk](https://github.com/alvarofdezr/Basilisk)** `Go`: Early-stage host monitor (processes, networking, hooks) that served as the architectural blueprint for *Aegis Sentinel*.
</details>

---

### Current Areas of Exploration
* **Kernel & eBPF Telemetry:** Exploring tracepoints and kprobes for low-overhead security monitoring.
* **Offensive Evasion Techniques:** Direct syscall invocation, API unhooking, and memory stealth.
* **Network Stack Internals:** Custom packet crafting and socket optimization in Go and C.

<br>

<div align="center">
  <i>"Each line of code written to learn more than what it teaches."</i>
</div>
