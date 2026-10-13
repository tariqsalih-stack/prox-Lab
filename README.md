# 🛠️ Home Lab Build & Infrastructure Stack

> **Status:** Active / Up & Running ⚡  
> **Location:** Office / Reptile Room  
> **Primary Hypervisor:** Proxmox VE  

Welcome to the documentation repository for my personal rack setup! This repository logs the physical hardware layout, network routing layer, and self-hosted services.

---

## 📄 Complete Documentation PDF
👉 **[View / Download Full Homelab Build PDF](Home%20Lab%20Build%20Documentation%20(1).pdf)**

---

## 🧰 Hardware Rack Schedule

| Rack Slot | Hardware | Category | Primary Function |
| :--- | :--- | :--- | :--- |
| **U1** | 24-Port Patch Panel | Cabling | Patch cabling and structured wall drop terminations |
| **U2** | Juniper EX2300-C-12P | Core Switch | Compact Layer 3 routing & main LAN gateway |
| **U3** | Extreme Networks X430-24t | Access Switch | Access layer switch for isolated lab subnets |
| **U4** | Cisco SG300-52MP | PoE Switch | 52-Port Gigabit Max-PoE switch for IP cameras |
| **U5 – U11** | Dell Precision T7910 | Compute Host | Dual Xeon Proxmox VE node (ZFS, Docker & Media) |
| **U12** | Tripp Lite SMART500RT1U | Battery Backup | 1U Line-interactive UPS & surge suppression |

---

## 🚀 Active & Planned Services

* 📦 **Proxmox VE:** Core hypervisor managing virtual machines and LXC containers.
* 💾 **TrueNAS:** Storage pool management and dataset sharing over ZFS.
* 🎬 **Jellyfin:** Self-hosted media streaming server.
* 📹 **Frigate NVR:** RTSP camera feed ingestion with local AI object detection.
* 🐳 **Docker:** Isolated runtime for web applications and telemetry services.
