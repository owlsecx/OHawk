# 🦅 OHawk

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-ORec%20%2F%20Network%20Scanning-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-None%20(stdlib)-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OHawk** is a high-speed multi-threaded IP range and port scanner with port detection, banner grabbing, OS hinting, risk scoring, live statistics, and structured TXT/JSON export.

**Fast, clean, and powerful network reconnaissance tool.**

---

## 📌 Overview

OHawk scans IP ranges or CIDR blocks against selected port profiles, identifies open services, grabs banners, provides OS hints via TTL, calculates per-host risk scores, and generates detailed reports.

Supports multiple scan modes and 8 built-in port profiles (Web, Database, Windows, IoT, Containers, etc.).

---

## 🖥️ Modules

| # | Module                  | Description |
|---|-------------------------|-------------|
| **[1]** | **Network Scan**        | Full IP × port scanner with risk scoring |
| **[2]** | **Host Discovery**      | TCP ping sweep to discover live hosts |

---

## 📊 Key Features

- **Multi-Mode Targeting** — Single IP, IP Range, or CIDR
- **8 Port Profiles** — Quick, Web, Database, Windows, IoT/ICS, Containers, Full 1-1024, Custom
- **Banner Grabbing** — Service identification and version detection
- **OS Hinting** — Best-effort OS detection via ICMP TTL
- **Risk Scoring** — Per-port and per-host risk levels (SAFE → CRITICAL)
- **Live Statistics** — Real-time progress, open ports count, scan rate
- **Structured Export** — Detailed TXT and JSON reports

---

## ⚙️ Requirements

- **No external dependencies** — Uses only Python standard library
- **Root/sudo on Linux** — Recommended for better ICMP/OS hinting (not strictly required)

**Standalone executable** — Runs as `./OHawk` when built with PyInstaller.

---

## 🚀 Usage

```bash
./OHawk

📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.
AUTHORISED SECURITY TESTING USE ONLY
