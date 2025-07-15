---
layout: default
title: SCADA Recon - Port 4443 Exposure
---

# 🔍 Industrial Control Systems: Port 4443 OSINT Recon

In July 2025, I conducted a passive reconnaissance effort focused on ICS/SCADA systems with exposed management interfaces.

## 🧠 Key Findings

- Publicly accessible devices exposing **port 4443** (commonly used for HTTPS).
- Multiple instances identified with **expired/self-signed certificates**.
- Some servers exposed `Schneider-Electric` headers and legacy HMI portals.
- Weak security practices — outdated software, default login pages, and no geo/IP restrictions.
- Targets ranged from **building automation** to **industrial control panels**.

## 📁 Evidence Repository

Detailed screenshots, fingerprints, and source IP data are archived here:  
👉 [Responsible Disclosures](https://github.com/OpenIntelHunter/responsible-disclosures)

## 🎯 Why It Matters

SCADA systems are critical, yet often exposed due to misconfigurations or poor vendor defaults. This effort reinforces the need for passive recon and responsible disclosure.

---

🧠 *OpenIntelHunter – OSINT-driven ICS awareness & advocacy.*

📬 For consulting or disclosure requests, contact me via GitHub.
