# 🌍 WorldView: Real-Time Geopolitical Intelligence & OSINT Dashboard

> **Live Production Environment**: [osint-worldview-ten.vercel.app](https://osint-worldview-ten.vercel.app)

---

## 💫 Introduction
**WorldView** is a premium, real-time geopolitical intelligence dashboard built for researchers, analysts, and security professionals. It aggregates and visualizes global signals across **45 interactive data layers** using a dual-engine mapping system (3D Globe and 2D WebGL Map), wrapped in a beautiful, retro-futuristic cyberpunk command center aesthetic.

Designed as a local-first, privacy-respecting platform, WorldView operates with an elegant **4-tier AI synthesis engine** that handles everything from local private LLMs to zero-cost cloud providers and on-device offline translation.

---

## ✨ Key Capabilities

### 🗺️ Dual-Engine Geospatial System
- **3D Interactive Globe**: Photorealistic rendering using `Three.js` and `globe.gl`.
- **2D WebGL Map**: Heatmaps and high-density clusters using `deck.gl` and `Maplibre`.
- **Sync & State persistence**: Transition seamlessly between 3D and 2D projections with active layers and camera states preserved.

### 📡 45+ Real-Time Geospatial Signals
- **Geopolitics & Conflict**: ACLED and UCDP events, global intelligence hotspots, and live sanction borders.
- **Strategic Logistics**: ADS-B transponder flight tracking and maritime AIS container ship congestion mapping.
- **Infrastructure & Assets**: Undersea internet cable routes, power grids, pipelines, nuclear plants, and data centers.
- **Natural Events**: Satellite fire detections (NASA FIRMS), storm forecasting, and USGS seismological activity.

### 🧠 Modern AI Architecture (BYOK & Fallbacks)
- **Local Ollama Support**: Run summaries completely private and offline on your machine.
- **Multi-Cloud Failover**: Auto-fallbacks between Groq, OpenRouter, and local models.
- **On-Device ML**: Light browser embedding translation and headline categorization.

---

## 🛠️ Technology Stack & Design

* **Core**: Modern Modular TypeScript, Vite, Custom Web Components.
* **Geospatial & Visuals**: `Three.js`, `globe.gl`, `deck.gl`, and `Maplibre GL`.
* **Desktop Wrapper**: Native Rust/Tauri secure wrapper for cross-platform desktop bundles.
* **Styling**: Cyberpunk-inspired glowing palettes using vanilla CSS tokens, high-contrast dark modes, and monospace typography.
* **Hosting**: Distributed edge hosting with instantaneous caching rules via **Vercel**.

---

## 🚀 Quick Start (Local Development)

### 1. Clone & Install
```bash
# Clone the repository
git clone https://github.com/khushijain/osint-worldview.git
cd osint-worldview

# Install the packages
npm install
```

### 2. Run the Development Server
```bash
npm run dev
```
Open **`http://localhost:3000`** (or the mapped local port) to preview the live dashboard.

---

## 👤 Credits & Authorization

**Built with ❤️ by [Khushi Jain](https://github.com/khushijain) | Geopolitical Intelligence Dashboard © 2026**
