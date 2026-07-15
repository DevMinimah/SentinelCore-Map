---
title: SentinelCore-Map
emoji: 🌍
colorFrom: blue
colorTo: gray
sdk: static
pinned: false
---

# SentinelCore: Critical Infrastructure Vulnerability Matrix

[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/Devminimah/SentinelCore-Map)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**🚀 Live Interactive Dashboard:** [Launch SentinelCore Map](https://huggingface.co/spaces/Devminimah/SentinelCore-Map)

## 📖 Project Overview
**SentinelCore** is a geospatial intelligence dashboard that models the intersection of environmental stressors and cyber-physical vulnerabilities across critical national infrastructure. Built for environmental scientists, GIS analysts, and cybersecurity professionals, it translates complex, interdisciplinary data into actionable risk matrices.

## 🛡️ Key Functionalities
* **Dual-Threat Vector Mapping:** Visualizes both environmental risks (e.g., coastal inundation, seismic liquefaction) and cyber-physical threats (e.g., exposed SCADA ports, BGP hijacking).
* **Dynamic Risk Scoring:** Implements a composite 0-100 Vulnerability Index, color-coded for rapid threat assessment.
* **Interactive Asset Registry:** Features bi-directional map-to-list linking, allowing analysts to filter by infrastructure class (Energy, Telecom, Oil & Gas, etc.) and fly to specific coordinates.
* **Zero-Backend Architecture:** Built entirely on client-side Leaflet.js and Tailwind CSS for rapid deployment and OPSEC safety.

## 🗺️ Infrastructure Classes Monitored
1. Power & Grid Distribution
2. Water Treatment & Reservoirs
3. Maritime Supply Ports
4. Transportation & Transit
5. Telecommunications & Data
6. Healthcare & Emergency Services
7. Agriculture & Food Systems
8. Oil, Gas & Petrochemicals
9. Educational & Research Institutions

## 🛠️ Tech Stack
* **Frontend:** HTML5, Tailwind CSS
* **Geospatial Engine:** Leaflet.js (CartoDB Dark Matter Basemap)
* **Hosting:** Hugging Face Spaces (Static)

## 📊 Use Cases
* **Academic Research:** Modeling climate change impacts on OT/ICS networks.
* **Policy Making:** Identifying high-priority zones for national infrastructure resilience funding.
* **Cybersecurity OSINT:** Visualizing attack surfaces in relation to physical environmental vectors.

---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

---
*Developed by [Devminimah] as part of an interdisciplinary portfolio bridging Environmental Science, GIS, and Cybersecurity.*