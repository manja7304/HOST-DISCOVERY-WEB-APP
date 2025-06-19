<h1 align="center">🌐 Host Discovery Tool</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Security-Network%20Recon-green?style=for-the-badge&logo=hackthebox" />
</p>

---

## 📖 Overview

**Host Discovery** is a Python-based tool for **scanning active hosts** in a given IP range or subnet. It works across both **Windows** and **Linux** and uses multiple techniques like:

- ICMP Echo Requests (Ping)
- TCP/UDP Probes
- Multi-threaded scanning

Useful for **network recon**, **penetration testing**, and **asset inventory** tasks.

---

## ⚙️ Features

- 🖥️ Cross-platform: Works on both Linux and Windows
- 🧠 Intelligent threading to speed up scans
- 📡 Supports CIDR input (e.g. `192.168.1.0/24`)
- 📜 Clean console output + optional file export
- 🔐 No need for elevated privileges (non-root fallback supported)

---

## 🧰 Requirements

- Python 3.6+
- Modules:
  - `ipaddress`
  - `socket`
  - `subprocess`
 
```bash
pip install -r requirements.txt
