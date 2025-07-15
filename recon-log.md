---
layout: default
title: Recon Log
permalink: /recon-log/
---

# 📡 Passive Recon Log

_This page is updated as new discoveries are made in the field of ICS/SCADA internet exposures._

## 🗓️ July 2025

- **[07-14]** 15+ Schneider-Electric devices exposing port `4443`, some using expired TLS, confirmed zenon panels
- **[07-12]** Found 6 Indusoft HMI web servers with no authentication on port `8080`
- **[07-10]** BACnet systems indexed on Shodan with firmware from 2014
- **[07-08]** Discovery of building management system with default login credentials via `Server: Niagara`

## 🛠️ Methodology

- Passive recon using search engines (Shodan, Censys, Fofa)
- Fingerprint by headers, TLS certs, favicon hashes
- Validate with GET/HEAD requests only — **no intrusion or exploitation**
