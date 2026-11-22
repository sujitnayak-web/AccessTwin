<div align="center">
  <h1>AccessTwin ♿🏛️</h1>
  <h3><i>"Find your destination. Follow the smartest route."</i></h3>
  <p><strong>Crowdsourced Accessibility Digital Twin for Public Buildings & Campuses</strong></p>
  <p><i>Smart India Hackathon / SOA Ideathon 2026 (Problem Statement: SOAIDEATHON-S37)</i></p>
  
  [![React](https://img.shields.io/badge/React-18.x-blue?style=flat-square&logo=react)](https://reactjs.org/)
  [![FastAPI](https://img.shields.io/badge/FastAPI-Python_3.11-009688?style=flat-square&logo=fastapi)](https://fastapi.tiangolo.com/)
  [![Supabase](https://img.shields.io/badge/Supabase-Database-3ECF8E?style=flat-square&logo=supabase)](https://supabase.com/)
</div>

---

## 📌 Links & Resources
* **Web page Link:** [Click here to watch](https://access-twin-jade.vercel.app/)
* **🎥 Live Demo Video:** [Click here to watch](https://youtu.be/cX1xIBF4Xcw?si=ZLj8DDvy2Krl5lR5)
* **📑 Pitch Deck / Presentation:** [View PPT Here](https://github.com/user-attachments/files/31342501/IDEATHON.PPT.pdf)

---

## 🚨 The Problem & Our Solution
In India, millions of citizens with physical or visual impairments struggle to navigate public buildings, educational campuses, and hospitals due to unmapped barriers like broken elevators, steep ramps, or blocked pathways. 

**AccessTwin** solves this by creating a real-time, interactive digital twin of any campus. We empower the community to crowdsource physical barriers, verify them using AI, and calculate customized obstacle-free paths. 

---

## ✨ Key Features

* 🗺️ **Interactive Spatial Digital Twin (Dijkstra's Algorithm):** Interactive SVG-based floor maps that map nodes across the campus. The system uses Dijkstra's algorithm to calculate the shortest, safest, and 100% obstacle-free route specifically tailored for wheelchair users.
* 🗣️ **Voice-Guided Wayfinding & Detection:** Full integration with the Web Speech API (`window.speechSynthesis`). The system provides human-like turn-by-turn auditory instructions for navigation and announces AI-detected obstacles for visually impaired users.
* 📸 **TwinGram (Gamified Social Feed):** A community-driven feed where students and visitors upload photos of physical barriers. The community confirms these issues, building a trustable "Confidence Score".
* 🤖 **AI Vision Intelligence (Gemini AI):** Uses Google Gemini's advanced multimodal capabilities for deep contextual analysis, detecting architectural features (like ramps and stairs), and generating automated, cost-effective repair recommendations.
* 📈 **Campus Accessibility Benchmark Index:** Automatically calculates an overall accessibility score for each building based on structural features, crowdsourced verified reports, and automated sensor audits.
* 🛠️ **Admin Dashboard & SVG Ingestion:** Administrators can view reports, plan fixes, and upload new SVG floor maps directly into the digital twin ecosystem.

---

## 📸 Application Screenshots


| Interactive Digital Twin Map | Turn-by-Turn Voice Navigation |
| :---: | :---: |
| <img src="Screenshot 2026-09-06 004331.png" width="100%" alt="Dashboard" /> | <img src="Screenshot 2026-09-06 004724.png" width="100%" alt="Turn-by-Turn voice nav" /> |

| TwinGram Social Feed | AI Barrier Detection |
| :---: | :---: |
| <img src="Screenshot 2026-09-06 004351.png" width="100%" alt="TwinGram Feed" /> | <img src="Screenshot 2026-09-06 004648.png" width="100%" alt="AI Detection" /> |

---

## 🛠️ Tech Stack & Architecture

**Frontend (Client)**
*   React 18, Vite, Tailwind CSS v4, Lucide React, Framer Motion
*   Interactive SVG Mapping & Web Speech API

**Backend (Server)**
*   Python 3.11.9, FastAPI, Uvicorn
*   NetworkX (Graph computation for Dijkstra routing)
*   Google GenAI SDK

**Database & Auth**
*   Supabase PostgreSQL (Structured relational data)
*   Supabase Storage (Secure image hosting)
*   Row Level Security (RLS) policies

---

## 🔮 Future Scope
* **IoT Sensor Integration:** Real-time data from automatic doors and elevators to update the digital twin instantly.
* **AR Navigation:** Augmented Reality directions overlaid on the smartphone camera for visually impaired users.

---

<p align="center"><i>Made with ❤️ and ☕</i></p>
