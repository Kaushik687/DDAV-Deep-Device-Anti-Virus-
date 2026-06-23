# DDAV — Deep Device Anti Virus

![Windows](https://img.shields.io/badge/Windows-10%2F11-blue)
![Python](https://img.shields.io/badge/Python-3.9%2B-green)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

A real, working Windows antivirus scanner with a professional GUI, 7 detection engines, and reversible threat blocking.

---

## What it does

| Feature | Description |
|---------|-------------|
| **Signature Scanning** | Hash + pattern matching against known malware |
| **PE Analysis** | Structural inspection of Windows executables |
| **Heuristic Detection** | Behavioral analysis (NOP sleds, obfuscation, encoded payloads) |
| **AMSI Integration** | Windows native script/memory scanning |
| **Registry Scan** | Persistence mechanism detection (Run keys, services, Winlogon hooks) |
| **Process Scan** | Active threat identification (masquerading, temp locations) |
| **Startup Scan** | Autorun and scheduled task detection |

Detects **25+ malware families** including ransomware, trojans, rootkits, spyware, cryptominers, worms, fileless malware, and AI-driven threats.

---

## Quick Start

### Option 1: Run the .exe (Recommended)
```powershell
# 1. Download the release ZIP
# 2. Extract to a folder
# 3. Right-click DDAV.exe → "Run as administrator"
