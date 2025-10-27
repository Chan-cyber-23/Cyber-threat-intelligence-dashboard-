# 🛡️ Cyber Threat Intelligence Dashboard

### 📌 Objective
The **Cyber Threat Intelligence (CTI) Dashboard** is a real-time web application that aggregates open threat intelligence feeds and visualizes Indicators of Compromise (IOCs).  
It allows users to input **IPs, domains, or URLs** and verify them against multiple threat intelligence APIs such as **VirusTotal** and **AbuseIPDB**.

---

### ⚙️ Features
- 🧩 Real-time IOC lookup for IPs and domains  
- 🌐 Integration with VirusTotal and AbuseIPDB APIs  
- 📊 Visualization of threat levels and trends using Chart.js  
- 🗂️ Tagging and exporting IOCs to CSV  
- 🔁 Automated data pulling using APScheduler  
- 🐳 Optional Docker deployment  

---

### 🏗️ Architecture Overview
- **Frontend:** HTML, CSS (Bootstrap), Chart.js  
- **Backend:** Flask (Python)  
- **Database:** MongoDB  
- **External APIs:** VirusTotal, AbuseIPDB  
- **Scheduler:** APScheduler (for periodic CTI feed updates)

---

### 📦 Installation & Setup

#### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/CyberThreatIntelligenceDashboard.git
cd CyberThreatIntelligenceDashboard
