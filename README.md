# 🚀 ASTROBASE
**Beyond Earth. Beyond Survival — An interactive 3D Moon-to-Mars space habitat simulator and space science trainer.**

🔗 **Play Live Demo:** [https://astrobaseweb.netlify.app](https://astrobaseweb.netlify.app)

---

## 📖 Introduction
**ASTROBASE** is an interactive 3D space colony simulator and educational platform designed to bring planetary science and off-world engineering to life. Built specifically for **students and young explorers (ages 7–12+)**, its core purpose is to turn complex spaceflight concepts—such as life-support loops, solar power storage, radiation shielding, and in-situ resource utilization (ISRU)—into hands-on, intuitive gameplay. Rather than simply reading about space exploration, children step into the role of a mission commander managing a 6-person crew across 30 days on the Moon or Mars, learning through experimentation how astronauts survive harsh environments beyond Earth.

---

## 🎮 Key Features & How It Helps Children Learn

### 1. Two Distinct Off-World Missions
Children can explore two iconic space destinations, each presenting unique scientific challenges:
- **Artemis: Lunar South Pole (Moon):** Teaches how an airless world experiences extreme temperature swings (`-175 °C` in shadow to `-45 °C` in sunlight), long 28-day shadow cycles where solar panels lose power, abrasive electrostatic lunar dust, and high cosmic radiation.
- **Red Planet: Jezero Crater (Mars):** Introduces players to a world with a thin carbon dioxide atmosphere, reduced solar efficiency, freezing nights, and multi-day regional dust storms that test energy reserves.

### 2. Interactive 3D Colony Builder
Using a real-time 3D terrain environment powered by Three.js, players purchase equipment from **13 specialized modules**—including Solar Arrays, Battery Banks, Oxygen Generators, Water Extractors, Greenhouses, Hydroponics, Radiation Shields, and Surface Rovers. Kids physically rotate and place structures onto slope-validated crater terrain, visually connecting where power is generated and how habitats are protected.

### 3. Color-Coded Resource & Survival Management
Starting with **1,000 Credits (CR)**, players monitor **Oxygen**, **Water**, **Food**, **Energy**, **Crew Health**, and **Base Integrity** using clear color-coded status bars (**Green** for Healthy, **Yellow** for Warning, and **Red** for Critical). Advancing day-by-day teaches cause-and-effect math: if oxygen runs low or batteries empty during an eclipse, crew health and base integrity drop.

### 4. Research Lab & Technology Unlocks
In the **Research Lab**, students invest credits and resources into multi-day scientific projects such as **Water Ice Detection**, **Regolith Shielding**, **Atmospheric Oxygen (MOXIE-inspired)**, **Planetary Geology**, and **Food Production**. Each project explains the real-world science behind the technology before unlocking advanced colony equipment.

### 5. Dynamic Space Hazards & Decision-Making
Throughout the 30-day mission, unexpected events—such as extended shadow periods, regional dust storms, solar flare radiation alerts, and equipment malfunctions—challenge young commanders to weigh trade-offs (e.g., sheltering the crew vs. conserving power) while reading a concise science explanation for every event.

### 6. Space Academy, Interactive Quizzes & Achievements
- **Space Academy:** Six child-friendly, bite-sized science articles covering the Lunar South Pole, lunar water ice, the Martian atmosphere, Jezero Crater, solar flares, and ISRU, each clearly separating real science facts from game assumptions.
- **Quiz Center:** Three interactive 5-question quizzes (**Moon Knowledge**, **Mars Knowledge**, and **Space Weather**) give instant feedback and explanations after every answer, rewarding kids with **4 CR per correct answer** (up to 20 CR per quiz) to fund their base.
- **Achievements & Mission Report:** Seven unlockable badges (such as *Efficient Commander*, *Master Researcher*, and *Sustainable Colony*) and a final commander rank motivate replayability and mastery.

---

## 🛰️ Datasets & Scientific References Used
These datasets are used across the simulator to inform environmental temperature ranges, solar illumination cycles, hazard events, and educational reference materials.

- **[LRO Diviner Lunar Radiometer Data Archive](https://www.diviner.ucla.edu/data)**
- **[NASA SVS 4574 — Lunar South Pole Illumination](https://svs.gsfc.nasa.gov/4574/)**
- **[LPI Lunar South Pole Atlas](https://www.lpi.usra.edu/lunar/lunar-south-pole-atlas/)**
- **[NASA PDS Curiosity MSL REMS Dataset](https://pds.nasa.gov/ds-view/pds/viewProfile.jsp?dsid=MSL-M-REMS-4-ENVRDR-V1.0)**
- **[Mars 2020 Perseverance Science Instruments (MEDA & MOXIE)](https://science.nasa.gov/mission/mars-2020-perseverance/science-instruments/)**
- **[NASA DONKI (Database Of Notifications, Knowledge, Information)](https://ccmc.gsfc.nasa.gov/tools/DONKI/)**

---

## 🛠️ Tech Stack & Project Structure
- **Frontend & UI:** HTML5, CSS3, Vanilla JavaScript (ES6+)
- **3D Graphics Engine:** [Three.js (r128)](https://threejs.org/) & `OrbitControls`
- **Data Persistence:** Browser `localStorage` for saving mission state, achievements, and quiz progress offline
- **Hosting:** Netlify


