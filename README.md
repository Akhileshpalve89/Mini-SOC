# 🛡️ Mini SOC Dashboard - SIEM-lite in Python

## 📌 Objective
A lightweight Security Operations Center (SOC) dashboard to monitor logs, detect threats, and visualize alerts from system and network logs.

## 🧰 Tools & Tech Used
- Python
- Flask (Web UI)
- SQLite (Storage)
- pyshark (PCAP parser)
- Chart.js / Plotly (Visualization)
- Linux logs (/var/log/)
- GeoIP API (optional)

## 🗂️ Project Structure
├── app.py 
├── templates/ 
│
└── dashboard.html 
├── static/ │
  └── charts.js 
├── parsers/ │ 
  └── authlog_parser.py │
  └── pcap_parser.py 
├── db/ │ 
  └── logs.db 
└── README.md



## 🔍 Features
- Real-time log monitoring
- Brute-force & port-scan detection
- IP-based threat visualization
- Exportable reports
- Modular codebase

## 🚀 Setup Instructions

```bash
git clone https://github.com/Akhileshpalve89/mini-soc-dashboard.git
cd mini-soc
pip install -r requirements.txt
python app.py
```

## 📊 Screenshots

## 📚 Skills Gained
- Python scripting
- Log parsing and threat detection
- SIEM fundamentals
- Flask web development
- Security visualization

## 🏁 Future Improvements
- Docker support
- Live feed via WebSocket
- Integration with remote agents

Created with ❤️ by Akhilesh Palve
---
