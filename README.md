# ThreatFeed: AI-Powered CTI Aggregator

**ThreatFeed** is a high-performance, browser-based Cyber Threat Intelligence (CTI) aggregator. It centralizes intelligence from 39+ sources, offering local AI analysis and a dedicated threat hunting workflow in a single, portable HTML file.

<img width="1501" height="628" alt="image" src="https://github.com/user-attachments/assets/e5ef20a4-7e0c-49fb-999d-af46d2de3e97" />


---

## 🚀 Key Features

* **Aggregation:** Real-time monitoring of 39+ CTI sources, including Mandiant, CISA, and Unit 42.
* **AI Analysis:** Built-in support for **Ollama** (Local), **Claude**, and **Gemini** to generate executive summaries and IOC extractions.
* **Threat Hunting:** Direct integration to convert articles into structured hunt tasks with AI auto-fill capabilities.
* **Privacy First:** Local LLM support and client-side data persistence using IndexedDB.

---

## 🛠 Setup & Requirements

### Local AI (Ollama) - Recommended
To keep your intelligence searches private and free, use [Ollama](https://ollama.com).

1. **Install Ollama** on your machine.
2. **Pull a model**:
   ```bash
   ollama pull llama3.2

# Starting Ollama with CORS Enabled

Required for browser access.

### macOS / Linux

OLLAMA_ORIGINS="*" ollama serve
### Windows

$env:OLLAMA_ORIGINS="*"; ollama serve
# 🔑 Commercial API Support


## You may optionally add API keys for:

- Claude
- Gemini

API keys can be entered in the sidebar settings panel.

## Security Notes

- Keys are stored only in volatile memory.
- Keys are sent directly to the respective API provider.
- Keys are not persisted or stored locally.




# ThreatFeed Application Overview

The ThreatFeed application aggregates intelligence from **39 curated sources**, categorized by their primary focus:
- Malware
- Vulnerabilities
- APTs (Advanced Persistent Threats)
- General news

---

## Core Intelligence & Malware Research
- **Talos Intel:** Broad spectrum threat intelligence from Cisco's research team.
- **SentinelOne Labs:** In-depth malware and behavioral analysis.
- **Check Point:** Global threat research and attack trends.
- **Unit 42:** High-fidelity intelligence from Palo Alto Networks.
- **Sophos Labs:** Advanced threat research and malware discoveries.
- **Huntress:** Tactical research focused on managed detection and response.
- **Gen Digital:** Broad cybersecurity and malware insights.
- **CrowdStrike:** Strategic intelligence on global adversaries and campaigns.
- **Zscaler ThreatLab:** Research into cloud-based threats and web malware.
- **Cybereason:** Advanced behavioral analysis and attack forensics.
- **Fortinet Threat Research:** Insights into emerging network and endpoint threats.
- **ReversingLabs:** Specialized focus on file-based malware and binary analysis.
- **Malwarebytes:** Comprehensive malware news and protection insights.

---

## APT & Targeted Campaign Analysis
- **Mandiant:** Expert-level reports on nation-state actors and major breaches.
- **Team Cymru:** Global infrastructure and internet security research.
- **DFIR Report:** Technical, case-study-driven analysis of real-world intrusions.
- **Kostas (Medium):** Targeted intelligence research and forensic findings.

---

## Vulnerability & Advisory Sources
- **CISA Advisories:** Official United States government cybersecurity warnings.
- **CISA Alerts:** Timely notification of high-priority vulnerabilities.
- **SANS ISC:** Global community-driven alerts on internet activity.
- **Microsoft SecBlog:** Official security updates and research from Microsoft.
- **Rapid7 Blog:** Vulnerability research and risk management insights.
- **Project Zero:** Google’s dedicated team finding zero-day vulnerabilities.
- **Detect FYI:** Advisory and detection engineering insights.
- **GoblinLoot:** Specialized advisory and security research. 
-**MS Sentinel Blog**: SIEM-specific detection and threat intelligence content. 	 	 	 	 	 	 	 	 	 	 	  
-**Cryptika**: Security advisories and technical findings.  

# 📝 License
This project is provided for educational and security research purposes. All intelligence remains the property of the respective RSS feed providers.
