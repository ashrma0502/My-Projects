# 👋 Hi, I'm Ayush Sharma

B.Tech CSE (AI & ML) student at GLA University. This repository is the single source of truth for my [portfolio site](https://ashrma0502.vercel.app/) — I only ever edit this file, and the site pulls project and certificate data from it automatically.

---

## 📂 Projects

### 🎓 College Projects

#### Frontend MCQ Test

Browser-based MCQ quiz app covering HTML, CSS, JavaScript, Bootstrap, and React — draws 15 random questions from a 50-question bank each attempt, with a scored, color-coded answer review.

- **Repo:** https://github.com/ashrma0502/Frontend-MCQ-Test
- **Tech:** HTML, CSS, JavaScript, Bootstrap

#### Seat Allocation Management System

Console-based C application for managing exam-hall seat allocation — assigns, releases, and searches seats in real time, with binary-file persistence and a timestamped activity log.

- **Repo:** https://github.com/ashrma0502/Seat-Allocation-System
- **Tech:** C

#### World Bank Data Pipeline

Production-style ETL pipeline that ingests World Bank economic indicators for five countries through a Bronze → Silver → Gold medallion architecture, with multithreaded extraction and layered data-quality gates, materialized in MySQL.

- **Repo:** https://github.com/ashrma0502/World-Bank-Pipeline
- **Tech:** Python, MySQL, pandas, SQLAlchemy

#### Flight Booking System

Normalized relational database modeling an end-to-end flight booking platform — users, airlines, airports, flights, bookings, payments, and passengers — seeded with sample data across 15 domestic and international airlines.

- **Repo:** https://github.com/ashrma0502/Flight-Booking-System
- **Tech:** MySQL

#### Myntra Clone

Pixel-perfect front-end clone of Myntra's e-commerce homepage — responsive navbar, promotional banners, brand and category carousels, and a 30+ item shop-by-category grid.

- **Repo:** https://github.com/ashrma0502/Myntra-Clone
- **Live:** https://myntracl.vercel.app
- **Tech:** HTML, CSS, Bootstrap

#### ATM Machine Simulator

Fully interactive browser-based ATM simulator with PIN authentication, deposits, withdrawals, printable receipts, and live transaction history — no backend required.

- **Repo:** https://github.com/ashrma0502/ATM-Machine
- **Live:** https://my-atm-system.vercel.app
- **Tech:** HTML, CSS, JavaScript, Bootstrap

#### QR Code Generator

Full-stack QR code generator supporting URL, text, email, Wi-Fi, and vCard formats with live preview and custom styling, split across a Streamlit frontend and a FastAPI backend.

- **Repo:** https://github.com/ashrma0502/Qr-Code-Generator
- **Frontend:** https://qr-generator-web.streamlit.app
- **Backend:** https://backend-qr-code.vercel.app
- **Tech:** FastAPI, Streamlit, Python, Pydantic

#### Weather Dashboard

Glassmorphism-styled weather dashboard with hourly and 5-day forecasts, a detailed atmospheric metrics grid, and saved favorite locations synced to local storage.

- **Repo:** https://github.com/ashrma0502/Weather-App
- **Live:** https://weather-focus.vercel.app
- **Tech:** React, Vite, Tailwind CSS, OpenWeatherMap API

#### Insure: Insurance Policy Management System

Full-stack insurance operations platform with role-based Admin, Agent, and Policyholder portals, a guarded claim-status workflow, and a full adjudication audit trail.

- **Repo:** https://github.com/ashrma0502/Insurance_Policy_Management
- **Tech:** Flask, Python, MySQL, Bootstrap

#### FraudShield: Real-Time Credit Card Fraud Detection Gateway

Full-stack web application for real-time payment fraud detection — screens each transaction with a rule engine and a Random Forest model, routes flagged payments to analyst review, and tracks live model performance, with JWT role-based access and email alerts.

- **Repo:** https://github.com/ashrma0502/FraudShield
- **Frontend:** https://fraudshield-gateway.vercel.app
- **Backend:** https://backend-fraudshield.vercel.app
- **Tech:** Python, Django, Django REST Framework, JWT auth, PostgreSQL, scikit-learn, React, Vite, Tailwind CSS, Vercel

### 🏆 Hackathon Projects

#### Smart Sign Language Translation System

Sensor-fusion sign language translator that combines webcam-based hand tracking (MediaPipe) with flex-sensor readings from an ESP32 smart glove, fusing both signals into a single gesture prediction with live confidence and stability scoring.

- **Repo:** https://github.com/ashrma0502/Smart-Sign-Language-Translation-System
- **Tech:** Python, FastAPI, MediaPipe, OpenCV, ESP32

### 🧑‍💻 Personal Projects

#### Math Suite

Browser-based computational workspace spanning 11 math domains — arithmetic through financial modeling — with core math logic kept independent of the UI and backed by 57 passing tests.

- **Repo:** https://github.com/ashrma0502/Math-Suite
- **Live:** https://math-suite.streamlit.app
- **Tech:** Python, Streamlit, NumPy, Matplotlib

#### Nexus

Multi-domain, real-time data intelligence platform — five dashboards pulling live data from 12 free public APIs into a DuckDB warehouse structured as a Bronze → Silver → Gold pipeline.

- **Repo:** https://github.com/ashrma0502/Nexus
- **Live:** https://project-nexus.streamlit.app
- **Tech:** Python, Streamlit, DuckDB, Plotly

---

## 📜 Certificates

Grouped by issuing platform — the underlying files live in the [Certificates repo](https://github.com/ashrma0502/Certificates).

| Issuer      | Link                                                                                    |
| ----------- | --------------------------------------------------------------------------------------- |
| Acmegrade   | [View certificates](https://github.com/ashrma0502/Certificates/tree/main/Acmegrade)     |
| CII Project | [View certificates](https://github.com/ashrma0502/Certificates/tree/main/CII%20Project) |
| HackerRank  | [View certificates](https://github.com/ashrma0502/Certificates/tree/main/HackerRank)    |
| Microsoft   | [View certificates](https://github.com/ashrma0502/Certificates/tree/main/Microsoft)     |
| Simplilearn | [View certificates](https://github.com/ashrma0502/Certificates/tree/main/Simplilearn)   |

---

<sub>This README doubles as the data source for my portfolio site. The two comment blocks below (`PROJECTS_JSON`, `CERTIFICATES_JSON`) are machine-readable and parsed automatically — edit them whenever a project or certificate is added, alongside the human-readable sections above.</sub>

<!-- PROJECTS_JSON
[
  {
    "name": "Frontend MCQ Test",
    "description": "Browser-based MCQ quiz app covering HTML, CSS, JavaScript, Bootstrap, and React — draws 15 random questions from a 50-question bank each attempt, with a scored, color-coded answer review.",
    "repo": "https://github.com/ashrma0502/Frontend-MCQ-Test",
    "techStack": ["HTML", "CSS", "JavaScript", "Bootstrap"],
    "type": "college"
  },
  {
    "name": "Seat Allocation Management System",
    "description": "Console-based C application for managing exam-hall seat allocation — assigns, releases, and searches seats in real time, with binary-file persistence and a timestamped activity log.",
    "repo": "https://github.com/ashrma0502/Seat-Allocation-System",
    "techStack": ["C"],
    "type": "college"
  },
  {
    "name": "World Bank Data Pipeline",
    "description": "Production-style ETL pipeline that ingests World Bank economic indicators for five countries through a Bronze → Silver → Gold medallion architecture, with multithreaded extraction and layered data-quality gates, materialized in MySQL.",
    "repo": "https://github.com/ashrma0502/World-Bank-Pipeline",
    "techStack": ["Python", "MySQL", "pandas", "SQLAlchemy"],
    "type": "college"
  },
  {
    "name": "Flight Booking System",
    "description": "Normalized relational database modeling an end-to-end flight booking platform — users, airlines, airports, flights, bookings, payments, and passengers — seeded with sample data across 15 domestic and international airlines.",
    "repo": "https://github.com/ashrma0502/Flight-Booking-System",
    "techStack": ["MySQL"],
    "type": "college"
  },
  {
    "name": "Myntra Clone",
    "description": "Pixel-perfect front-end clone of Myntra's e-commerce homepage — responsive navbar, promotional banners, brand and category carousels, and a 30+ item shop-by-category grid.",
    "repo": "https://github.com/ashrma0502/Myntra-Clone",
    "links": {
      "live": "https://myntracl.vercel.app"
    },
    "techStack": ["HTML", "CSS", "Bootstrap"],
    "type": "college"
  },
  {
    "name": "ATM Machine Simulator",
    "description": "Fully interactive browser-based ATM simulator with PIN authentication, deposits, withdrawals, printable receipts, and live transaction history — no backend required.",
    "repo": "https://github.com/ashrma0502/ATM-Machine",
    "links": {
      "live": "https://my-atm-system.vercel.app"
    },
    "techStack": ["HTML", "CSS", "JavaScript", "Bootstrap"],
    "type": "college"
  },
  {
    "name": "QR Code Generator",
    "description": "Full-stack QR code generator supporting URL, text, email, Wi-Fi, and vCard formats with live preview and custom styling, split across a Streamlit frontend and a FastAPI backend.",
    "repo": "https://github.com/ashrma0502/Qr-Code-Generator",
    "links": {
      "frontend": "https://qr-generator-web.streamlit.app",
      "backend": "https://backend-qr-code.vercel.app"
    },
    "techStack": ["FastAPI", "Streamlit", "Python", "Pydantic"],
    "type": "college"
  },
  {
    "name": "Weather Dashboard",
    "description": "Glassmorphism-styled weather dashboard with hourly and 5-day forecasts, a detailed atmospheric metrics grid, and saved favorite locations synced to local storage.",
    "repo": "https://github.com/ashrma0502/Weather-App",
    "links": {
      "live": "https://weather-focus.vercel.app"
    },
    "techStack": ["React", "Vite", "Tailwind CSS", "OpenWeatherMap API"],
    "type": "college"
  },
  {
    "name": "Insure: Insurance Policy Management System",
    "description": "Full-stack insurance operations platform with role-based Admin, Agent, and Policyholder portals, a guarded claim-status workflow, and a full adjudication audit trail.",
    "repo": "https://github.com/ashrma0502/Insurance_Policy_Management",
    "techStack": ["Flask", "Python", "MySQL", "Bootstrap"],
    "type": "college"
  },
  {
    "name": "Smart Sign Language Translation System",
    "description": "Sensor-fusion sign language translator that combines webcam-based hand tracking (MediaPipe) with flex-sensor readings from an ESP32 smart glove, fusing both signals into a single gesture prediction with live confidence and stability scoring.",
    "repo": "https://github.com/ashrma0502/Smart-Sign-Language-Translation-System",
    "techStack": ["Python", "FastAPI", "MediaPipe", "OpenCV", "ESP32"],
    "type": "hackathon"
  },
  {
    "name": "Math Suite",
    "description": "Browser-based computational workspace spanning 11 math domains — arithmetic through financial modeling — with core math logic kept independent of the UI and backed by 57 passing tests.",
    "repo": "https://github.com/ashrma0502/Math-Suite",
    "links": {
      "live": "https://math-suite.streamlit.app"
    },
    "techStack": ["Python", "Streamlit", "NumPy", "Matplotlib"],
    "type": "personal"
  },
  {
    "name": "Nexus",
    "description": "Multi-domain, real-time data intelligence platform — five dashboards pulling live data from 12 free public APIs into a DuckDB warehouse structured as a Bronze → Silver → Gold pipeline.",
    "repo": "https://github.com/ashrma0502/Nexus",
    "links": {
      "live": "https://project-nexus.streamlit.app"
    },
    "techStack": ["Python", "Streamlit", "DuckDB", "Plotly"],
    "type": "personal"
  },
  {
    "name": "FraudShield: Real-Time Credit Card Fraud Detection Gateway",
    "description": "Full-stack web application for real-time payment fraud detection — screens each transaction with a rule engine and a Random Forest model, routes flagged payments to analyst review, and tracks live model performance, with JWT role-based access and email alerts.",
    "repo": "https://github.com/ashrma0502/FraudShield",
    "links": {
      "frontend": "https://fraudshield-gateway.vercel.app/",
      "backend": "https://backend-fraudshield.vercel.app/"
    },
    "techStack": ["Python", "Django, "Django REST Framework", "JWT auth", "PostgreSQL", "scikit-learn", "React", "Vite", "Tailwind CSS", "Vercel"],
    "type": "college"
  }
]
PROJECTS_JSON_END -->

<!-- CERTIFICATES_JSON
[
  { "issuer": "Acmegrade", "folder": "https://github.com/ashrma0502/Certificates/tree/main/Acmegrade" },
  { "issuer": "CII Project", "folder": "https://github.com/ashrma0502/Certificates/tree/main/CII%20Project" },
  { "issuer": "HackerRank", "folder": "https://github.com/ashrma0502/Certificates/tree/main/HackerRank" },
  { "issuer": "Microsoft", "folder": "https://github.com/ashrma0502/Certificates/tree/main/Microsoft" },
  { "issuer": "Simplilearn", "folder": "https://github.com/ashrma0502/Certificates/tree/main/Simplilearn" }
]
CERTIFICATES_JSON_END -->
