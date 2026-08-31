# ⚡ Omarchy Antigravity Nexus & Bootstrap System

[![OS - Omarchy](https://img.shields.io/badge/OS-Omarchy%20(Arch%20Linux)-00f0ff?style=for-the-badge&logo=archlinux&logoColor=black)](https://github.com/FreeFades2Black/omarchy-antigravity-bootstrap)
[![Hardware - ASUS ROG Flow Z13](https://img.shields.io/badge/Hardware-ASUS%20ROG%20Flow%20Z13-ff007f?style=for-the-badge&logo=asus&logoColor=white)](https://github.com/FreeFades2Black/omarchy-antigravity-bootstrap)
[![Compositor - Hyprland](https://img.shields.io/badge/Compositor-Hyprland%20v0.56.2-ffe600?style=for-the-badge&logo=wayland&logoColor=black)](https://github.com/FreeFades2Black/omarchy-antigravity-bootstrap)
[![Agent - Google Antigravity](https://img.shields.io/badge/Agent-Google%20Antigravity%20(agy)-00ff9f?style=for-the-badge&logo=google&logoColor=black)](https://github.com/FreeFades2Black/omarchy-antigravity-bootstrap)
[![Commits - 300+ Native Omarchy](https://img.shields.io/badge/Commits-300%2B%20Native%20Omarchy-d600ff?style=for-the-badge&logo=git&logoColor=white)](https://github.com/FreeFades2Black/omarchy-antigravity-bootstrap)

> 🛡️ **Attestation of Origin:** Every script, configuration, doc, and commit in this repository was authored, tested, and pushed directly from the **Omarchy OS** workstation on an ASUS ROG Flow Z13.

---

## 🌌 Overview

The **Omarchy Antigravity Nexus** is a complete, automated blueprint demonstrating:
1. **Self-Healing Arch Linux / Omarchy System:** Automated DNS stub resolver fixes (`systemd-resolved`), 8GB swap allocation, SSD periodic TRIM, and package hygiene.
2. **Glassmorphic Cyberpunk Hyprland Aesthetics:** Multi-pass blur, custom translucent opacities, tri-color neon active borders, glowing Waybar telemetry, and ASUS ROG Flow Z13 keyboard RGB synchronization.
3. **Recursive Antigravity Deployment ("Agent-in-Agent"):** How a local Antigravity AI assistant can connect via SSH to an Omarchy machine and autonomously deploy, configure, and orchestrate a secondary native Antigravity instance.
4. **Seamless GitHub Integration:** Automatic token exchange, key configuration, and 300+ granular commits pushed natively from the Linux host.

---

## 🛠️ Hardware & Environment Attestation

| Spec | Target Machine Profile |
| :--- | :--- |
| **Operating System** | **Omarchy OS** (Arch Linux Rolling, Kernel `7.1.9-arch1-2`) |
| **Hardware** | **ASUS ROG Flow Z13 (GZ301VU)** |
| **GPU Stack** | Intel Iris Xe + NVIDIA GeForce RTX 4050 Laptop GPU (`610.57.04`) |
| **Window Manager** | **Hyprland `v0.56.2`** (Wayland) on LG UltraGear 144Hz |
| **AI Assistant** | **Google Antigravity CLI (`agy v1.1.22`)** |
| **Terminal / Shell** | Kitty / Alacritty / Ghostty with Cyberpunk Palettes & Zsh/Bash |

---

## 🚀 Quickstart

```bash
# 1. Run Complete Omarchy System Diagnostics & Healing
bash scripts/01_omarchy_diagnostics.sh

# 2. Install Cyberpunk Theme Engine & Glassmorphism
bash scripts/02_cyberpunk_theme_installer.sh

# 3. Bootstrap Native Antigravity CLI & Hyprland Super+A Hotkey
bash scripts/04_antigravity_installer.sh
```

---

## 📜 Commit Provenance
Every single commit in this repository includes Git trailers verifying its execution on Omarchy:
```text
Origin-OS: Omarchy (Arch Linux)
Hardware: ASUS ROG Flow Z13 (GZ301VU)
Compositor: Hyprland v0.56.2 (Wayland)
Committed-From: Omarchy Linux Workstation
Signed-off-by: Free <whall4.wh@gmail.com>
```

---

## 🔍 Internal Code Architecture & Comprehensive Inline Documentation

> **Comprehensive Codebase Documentation Audit Completed (2026)**
> Every core module, function, class, and critical execution path across this repository has been audited and enriched with detailed internal inline comments (`# ...`) and comprehensive docstrings. Anyone reading the source code can immediately trace the operational mechanics, data flow, failure recovery strategies, and architectural decisions.

### 🧩 Key Codebase Modules & Internal Mechanics Walkthrough

| File / Component | Purpose & Internal Mechanics |
| :--- | :--- |
| [`agent/recursive_orchestrator.py`](agent/recursive_orchestrator.py) | Multi-agent process manager spawning and monitoring autonomous execution workers. |
| [`agent/hypr_ipc.py`](agent/hypr_ipc.py) | Real-time Hyprland Wayland IPC socket client managing window focus, geometry, and workspaces. |
| [`agent/telemetry.py`](agent/telemetry.py) | System resource collector gathering CPU, GPU, memory, and task latency metrics. |
| [`agent/systemd.py`](agent/systemd.py) | User-space systemd unit controller managing background daemon lifecycle. |
| [`agent/watchdog.py`](agent/watchdog.py) | Liveness watchdog automatically restarting stalled or deadlocked agent threads. |

### 💡 Developer & Maintainer Guidelines
- **Inline Documentation Standard:** Every non-trivial logic branch, data transformation, API integration, and error block includes descriptive line-by-line internal notes.
- **Traceability:** Function signatures declare explicit type annotations (`typing.Dict`, `typing.List`, `typing.Optional`) and descriptive parameter/return docstrings.
- **Error Resilience:** Try/except blocks document exact failure modes, fallback pathways, and logging formats.
