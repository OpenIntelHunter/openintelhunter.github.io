---
layout: post
title: "OpenIntelHunter — OSINT & SCADA Recon"
---
title: SCADA OSINT Exposure – July 2025
---

# SCADA Recon: Port 4443 Findings

In July 2025, a passive reconnaissance operation revealed a series of industrial systems exposing port `4443` to the public internet.

## Key Findings

- ✅ Devices found running on port `4443`
- 🛑 Most using self-signed or expired TLS certificates
- ⚠️ Some still responded with `Server: Schneider-Electric` headers
- 🚨 Many endpoints led to outdated HMI web interfaces (e.g., Citect, zenon, Indusoft)

## Screenshots & Evidence

Artifacts are stored in the [responsible-disclosures](https://github.com/OpenIntelHunter/responsible-disclosures) repo.

## Intent

This post highlights the lack of secure configurations and visibility in ICS/SCADA systems — a reminder that air-gaps are often myths.

---

📧 For consulting or responsible disclosure inquiries, contact via GitHub.
