# 🌍 Global Honeypot Attack Analysis (Azure Sentinel – May 2025)

This project simulates a vulnerable Windows 10 endpoint deployed as a honeypot in Microsoft Azure to capture real-world brute-force login attempts. Logs were ingested into Microsoft Sentinel via Log Analytics Workspace (LAW) and enriched using a custom GeoIP watchlist to visualize attacker behavior and geographic origin.

## 🔍 Key Features
- 🚨 **Live honeypot** VM with exposed RDP port (3389)
- 📊 **Azure Sentinel dashboards** for attack trends and maps
- 🌐 **GeoIP enrichment** via watchlist and `ipv4_lookup()`
- 🧠 Real-time analytics using **Kusto Query Language (KQL)**
- 📈 Visuals: time-series, heatmaps, bar and pie charts
- 🧾 Full LaTeX report documenting setup, queries, and insights


## 🛠 Technologies Used
- Microsoft Azure (VM, LAW, Watchlists, Workbooks)
- Microsoft Sentinel
- KQL (Kusto Query Language)
- LaTeX

## 📊 Project Highlight
Captured over **40,000+ login attempts** across **15+ countries**, with notable surges from Argentina, Brazil, and Slovenia. This project showcases end-to-end threat intelligence workflows using Sentinel and custom telemetry enrichment.

## 📚 Author
**Vishvajith Ganesh**  
Role: SOC Analyst / Student Researcher  
Date: May 2025

---

> This project was designed for educational and research purposes only.
> VM stopped as of 16:17 on May 22 2025
