# 🚀 AFTERLIFE OF SPACE
### *Abandoned but Not Forgotten — The Mission Ended. The Story Didn’t.*

[![NASA Space Apps Challenge 2026](https://img.shields.io/badge/NASA_Space_Apps-2026_Challenge-38BDF8?style=for-the-badge)](https://www.spaceappschallenge.org/)
[![Status](https://img.shields.io/badge/Status-Interactive_Museum_Live-10B981?style=for-the-badge)]()
[![Tech Stack](https://img.shields.io/badge/Frontend-HTML5_%7C_TailwindCSS_%7C_Vanilla_JS-F97316?style=for-the-badge)]()

> **"Every machine leaves a legacy. The mission ended. The story didn't."**

**AFTERLIFE OF SPACE** is an interactive digital museum, planetary radar explorer, and educational storytelling platform created for the **NASA Space Apps Challenge 2026** (*"Abandoned but not forgotten: Storytelling about NASA's discarded equipment on the Moon and Mars"*).

Instead of presenting raw spreadsheets or dry dashboards, this platform transforms open-source NASA planetary data into living, first-person narratives told by the machines themselves—turning school-age learners, educators, and space enthusiasts into **Space Archaeologists**.

---

## 🎯 The Problem & Our Solution
“Abandoned but not forgotten: Storytelling about NASA’s discarded equipments on the Moon and the Mars.”
Since 1960s, NASA has left hardware across the solar system-on the Moon, on Mars and in deep space. From rovers and instruments that completed their science missions to probes still traveling away from Earth this hardware varies widely in both its purpose and current level of functionality. Your challenge is to tell the story of some or all of its equipment that introduces school-age space enthusiasts to hardware and the science it made possible.
Millions of students know about historic Apollo Moon landings and Mars rovers, yet few know **what happened afterward**, **why hardware was left behind**, **what lasting discoveries were made**, or **how those dormant relics shape today's Artemis and Mars missions**.

**Our Approach:**
* **Traditional Dashboards:** `NASA Open Data → Static Charts → Passive Reading`
* **Afterlife of Space:** `NASA Open Data → Forgotten Machine → First-Person Story → Interactive Discovery → Human Legacy`

---

## ✨ Key Interactive Features

1. **📡 Dual-World Coordinate Radar Explorer (Luna & Mars)**
   * Interactive topographic radar interface with sweeping scan beams, crater/canyon contours, and multi-layer toggles (*Radar Scan*, *LOLA/MOLA Elevation Contours*, and *Orbital Reconnaissance*).
   * Clickable surface beacons mapped to authentic IAU planetocentric coordinates.
2. **🎙️ "Wake the Machine" First-Person Console**
   * Select any of the **8 iconic lunar and Martian artifacts** to boost gain on its antenna, triggering an animated audio equalizer, typewriter monologue, and synthesized Web Speech voiceover in the machine's own persona.
3. **💬 In-Character AI Deep-Space Relay**
   * Ask spacecraft questions directly (*"What did you discover?"*, *"Were you lonely?"*, *"Why were you left behind?"*) and receive scientifically accurate, child-friendly answers grounded in mission telemetry.
4. **🔬 Interactive Science Discovery Pipelines & Legacy Engine**
   * Step-by-step visual pipelines tracing raw sensor readings to major scientific breakthroughs (e.g., *Hematite "Blueberries" → Ancient Liquid Water → Habitability Potential → Sample Return*).
   * **Legacy Engine** impact meters measuring *Scientific*, *Educational*, and *Exploration* contributions.
5. **🏺 Space Archaeologist Gamification & Field Log**
   * Earn XP as you scan worlds, wake dormant machines, inspect datasets, and interview spacecraft—progressing from **Cadet Observer** to **Mission Commander**, complete with a claimable **Certificate of Planetary Archaeology**.
6. **📊 Open Planetary Data Center & Classroom Export**
   * Full data provenance transparency with PDS4 Bundle URNs, NSSDC catalog IDs, live NASA Image Library queries, and one-click **JSON** and **CSV** telemetry exports for STEM classrooms.
7. **⏳ Chronological Mission Timeline (1967 → Present) & Future STEM Matcher**
   * Interactive timeline spanning *Surveyor 3* to *Ingenuity*, paired with a STEM career matcher connecting past hardware to future careers.

---

## 🛰️ Tracked Planetary Artifacts

| World | Hardware Artifact | Year(s) | Landing Coordinates | Key Legacy |
| :--- | :--- | :--- | :--- | :--- |
| **Moon** | **Surveyor 3** | 1967 | `3.016° S, 336.582° E` | Proved lunar soil bearing strength; visited by Apollo 12 |
| **Moon** | **Apollo 11 Eagle Descent Stage** | 1969 | `0.6741° N, 23.4730° E` | First human touchdown; active Laser Retroreflector |
| **Moon** | **ALSEP Geophysical Network** | 1969–1977 | `3.6453° S, 342.5284° E` | Logged 13,000+ moonquakes over 8 continuous years |
| **Moon** | **Apollo 15 Lunar Roving Vehicle** | 1971 | `26.1322° N, 3.6339° E` | First electric car off-world; enabled Genesis Rock discovery |
| **Mars** | **Sojourner Mars Rover** | 1997 | `19.33° N, 33.55° W` | First wheeled rover on Mars; pioneered rocker-bogie suspension |
| **Mars** | **Opportunity Rover (MER-B)** | 2004–2018 | `1.9462° S, 354.4734° E` | Drove 45.16 km marathon; found water-formed hematite spheres |
| **Mars** | **InSight Geophysical Lander** | 2018–2022 | `4.5024° N, 135.6234° E` | Detected 1,319 marsquakes; mapped Mars's liquid core |
| **Mars** | **Ingenuity Mars Helicopter** | 2021–2024 | `18.4447° N, 77.4508° E` | Completed 72 powered flights in 1% Martian atmosphere |

---

## 🏛️ Legal Open-Source NASA Data & Resource Links

To ensure absolute scientific validity and legal compliance, all telemetry, catalogs, and imagery utilized in this project are drawn directly from official open-access NASA repositories under public domain / open data usage policies:

* **[NASA Planetary Data System (PDS)](https://pds.nasa.gov/):** Access calibrated rover mobility logs, Mössbauer elemental spectra, and seismic waveform bundles.
* **[NASA Image and Video Library API](https://images.nasa.gov/):** Public-domain mission photography, surface panoramas, and engineering telemetry imagery via the [Images API Endpoints](https://images-api.nasa.gov/).
* **[Lunar Reconnaissance Orbiter Camera (LROC) & LOLA Elevation Data](https://lroc.sese.asu.edu/):** High-resolution lunar surface imaging and 0.5 m/pixel topography data managed by NASA Goddard and Arizona State University.
* **[Mars Global Surveyor MOLA & MRO HiRISE Topography](https://hirise.lpl.arizona.edu/):** Martian surface elevation topography and high-resolution orbital lander spotting.
* **[NSSDC Master Spacecraft Archive](https://nssdc.gsfc.nasa.gov/):** Master catalog identifiers, spacecraft launch manifests, and mission landing coordinates.
* **[NASA Solar System Treks (Moon Trek & Mars Trek)](https://trek.nasa.gov/):** Interactive web-based GIS visualization portals used for coordinate reference and topographic cross-referencing.

---

## 🛠️ Tech Stack & Architecture

* **Architecture:** Single-file responsive web application (`index.html`) with inline scripting logic using JavaScript designed for instant deployment, speed, and offline classroom resilience.
* **Styling & UI:** Tailwind CSS and BootStrap with custom glassmorphism, obsidian telemetry HUD, and responsive grid layouts.
* **Graphics & Visualization:** Custom procedural SVG spacecraft schematics, interactive radar coordinate engine, and HTML5 Canvas starfield.
* **Audio & Interactivity:** Native Web Speech API (`speechSynthesis`) for first-person machine voiceovers paired with typewriter telemetry rendering.

---

## 🚀 Quick Start:

Because **AFTERLIFE OF SPACE** is built as a self-contained frontend application with zero external build dependencies, running it takes seconds:


   * Visit `https://afterlife-of-space-the-mission-ended-the.onrender.com/#explorer` in your browser.

---

## 📜 Compliance Note

* All NASA datasets, orbital coordinates, and public-domain imagery are used in accordance with **NASA Open Data** and **NASA Media Usage Guidelines**.
* In strict adherence to NASA Space Apps Challenge branding rules, this project uses **100% original geometric emblems and custom vector illustrations**—no official NASA logos, insignias, or mission patches are used.

---

*Built with curiosity for the NASA Space Apps Challenge 2026.* 🌌
