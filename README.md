# OSINT – Invisible Footprint
### Autonomous Multi-Modal OSINT Intelligence Platform

An end-to-end OSINT system that autonomously collects, correlates, analyzes, and visualizes publicly exposed digital footprints to assess exposure risk — built with a strong focus on ethics, scalability, and real-world cyber intelligence use cases.

---

## 🚀 Key Features

### 🔍 Multi-Modal Intelligence Fusion
Collects and correlates intelligence from multiple public data modalities:
- **Text OSINT** – usernames, emails, documents, posts
- **Image OSINT** – EXIF metadata, reverse image analysis
- **Video OSINT** – multi-frame analysis, landmark inference
- **Audio OSINT** – metadata & contextual signals (where applicable)
- **Code Repositories** – commit history, identity leakage
- **Geospatial Signals** – location inference from public artifacts

### 🧠 Autonomous Self-Learning Agent
- Continuous OSINT scanning without manual triggers
- Differential exposure detection (what changed over time)
- Pattern learning from previous scans
- Adaptive discovery of new sources and signals

---

### 🔁 Reverse OSINT Intelligence
Turns surveillance inward to detect tracking and monitoring risks:
- Tracker & scraper detection
- Surveillance and indexing inference
- Dark-web & breach correlation (where public references exist)

---

### 🧩 Unified Intelligence Graph
- Cross-platform identity linking
- Temporal correlation of signals
- Network and relationship analysis
- Graph-based intelligence representation

### ⚠️ Exposure Classification & Risk Scoring
Automatically classifies exposed signals:
- PII
- Credentials
- Behavioral patterns
- Sensitivity & exploitability
- Recency-based risk weighting

Generates an **explainable risk score** for each entity.

---

### 📊 Interactive Visual Dashboard
- Live intelligence graphs
- Risk indicators
- Platform-wise exposure breakdown
- Drill-down analytics for investigators

###  Live Demo
End-to-end demo flow:
**Input → Scan → Correlate → Visualize → Risk Score**
(All within minutes)


## 🏗 High-Level Architecture
```text
Public Open Sources
        ↓
Multi-Modal OSINT Data Collection
        ↓
Normalization, Correlation & Reverse OSINT
        ↓
Exposure Classification
        ↓
Risk Scoring + Explanation
        ↓
Unified Digital Footprint Graph
        ↓
Autonomous Monitoring Engine
        ↺ (feeds back into Data Collection)
``` 

## 📂 Project Structure
```text
OSINT-INVISIBLE-FOOTPRINT/
│
├── requirements.txt
│
├── WEB/
│   ├── static/
│   │   └── style.css
│   ├── templates/
│   │   ├── index.html
│   │   └── result.html
│   ├── app.py
│   └── dashboard_app.py
│
├── OSINT/
│   ├── __init__.py
│   ├── analysis/
│   │   ├── intel_graph.py
│   │   └── scan2.json
│   ├── core/
│   │   ├── autonomous_agent.py
│   │   ├── orchestrator.py
│   │   └── risk_engine.py
│   ├── features/
│   │   ├── image_osint.py
│   │   ├── repo_osint.py
│   │   ├── text_osint.py
│   │   ├── tracker_detection.py
│   │   └── video_osint.py
│   └── utils/
│       ├── helpers.py
│       └── __init__.py
│
├── .gitignore
├── LICENSE
└── README.md

```

## 👥 Team Workflow
- Feature-based ownership
- One feature → one contributor
- All changes via Pull Requests
- main branch is protected
- No direct pushes to main

## 🔐 Ethics & Privacy
This system:
- Uses only publicly accessible data
- Avoids private or unauthorized sources
- Does not perform facial recognition
- Focuses on awareness, not surveillance
- Enforces ethical boundaries in both code and documentation
- Ethics is treated as a core system component, not an afterthought.

## ⚠ Disclaimer
- This project is intended strictly for educational, research, and awareness purposes.
- It does not promote surveillance, harassment, or misuse of OSINT techniques.

## 📜 License
- Licensed under the MIT License.

## 📌 Status
- 🚧 Under active development
- Feature implementation is ongoing via Pull Requests.
