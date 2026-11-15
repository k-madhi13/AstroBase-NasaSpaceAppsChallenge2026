# AstroBase-NasaSpaceAppsChallenge2026
# ASTROBASE
**Beyond Earth. Beyond Survival — An interactive 3D Moon-to-Mars space habitat simulator and space science trainer.**

🔗 **Play Live Demo:** [https://your-project-name.netlify.app](https://astrobaseweb.netlify.app)]

---

## 📖 Introduction
**ASTROBASE** is an interactive 3D space colony simulator and educational platform designed to bring planetary science and off-world engineering to life. Built specifically for **students and young explorers (ages 7–12+)**, its core purpose is to turn complex spaceflight concepts—such as life-support loops, solar power storage, radiation shielding, and in-situ resource utilization (ISRU)—into hands-on, intuitive gameplay[cite: 12]. Rather than simply reading about space exploration, children step into the role of a mission commander managing a 6-person crew across 30 days on the Moon or Mars, learning through experimentation how astronauts survive harsh environments beyond Earth[cite: 12].

---

## 🎮 Key Features & How It Helps Children Learn

### 1. Two Distinct Off-World Missions
Children can explore two iconic space destinations, each presenting unique scientific challenges[cite: 12]:
* **Artemis: Lunar South Pole (Moon):** Teaches how an airless world experiences extreme temperature swings (`-175 °C` in shadow to `-45 °C` in sunlight), long 28-day shadow cycles where solar panels lose power, abrasive electrostatic lunar dust, and high cosmic radiation[cite: 12].
* **Red Planet: Jezero Crater (Mars):** Introduces players to a world with a thin carbon dioxide atmosphere, reduced solar efficiency, freezing nights, and multi-day regional dust storms that test energy reserves[cite: 12].

### 2. Interactive 3D Colony Builder
Using a real-time 3D terrain environment powered by Three.js, players purchase equipment from **13 specialized modules**—including Solar Arrays, Battery Banks, Oxygen Generators, Water Extractors, Greenhouses, Hydroponics, Radiation Shields, and Surface Rovers[cite: 12]. Kids physically rotate and place structures onto slope-validated crater terrain, visually connecting where power is generated and how habitats are protected[cite: 12].

### 3. Color-Coded Resource & Survival Management
Starting with **1,000 Credits (CR)**, players monitor **Oxygen**, **Water**, **Food**, **Energy**, **Crew Health**, and **Base Integrity** using clear color-coded status bars (**Green** for Healthy, **Yellow** for Warning, and **Red** for Critical)[cite: 12]. Advancing day-by-day teaches cause-and-effect math: if oxygen runs low or batteries empty during an eclipse, crew health and base integrity drop[cite: 12].

### 4. Research Lab & Technology Unlocks
In the **Research Lab**, students invest credits and resources into multi-day scientific projects such as **Water Ice Detection**, **Regolith Shielding**, **Atmospheric Oxygen (MOXIE-inspired)**, **Planetary Geology**, and **Food Production**[cite: 12]. Each project explains the real-world science behind the technology before unlocking advanced colony equipment[cite: 12].

### 5. Dynamic Space Hazards & Decision-Making
Throughout the 30-day mission, unexpected events—such as extended shadow periods, regional dust storms, solar flare radiation alerts, and equipment malfunctions—challenge young commanders to weigh trade-offs (e.g., sheltering the crew vs. conserving power) while reading a concise science explanation for every event[cite: 12].

### 6. Space Academy, Interactive Quizzes & Achievements
* **Space Academy:** Six child-friendly, bite-sized science articles covering the Lunar South Pole, lunar water ice, the Martian atmosphere, Jezero Crater, solar flares, and ISRU, each clearly separating real science facts from game assumptions[cite: 12].
* **Quiz Center:** Three interactive 5-question quizzes (**Moon Knowledge**, **Mars Knowledge**, and **Space Weather**) give instant feedback and explanations after every answer, rewarding kids with **4 CR per correct answer** (up to 20 CR per quiz) to fund their base[cite: 12].
* **Achievements & Mission Report:** Seven unlockable badges (such as *Efficient Commander*, *Master Researcher*, and *Sustainable Colony*) and a final commander rank motivate replayability and mastery[cite: 12].

---

## 🛰️ Datasets & Scientific References Used
ASTROBASE models its environmental ranges, planetary hazards, and educational modules on official NASA and planetary science datasets[cite: 12]. *(To maintain scientific honesty for young learners, all in-game numerical rates are explicitly labeled as simulated game-balance parameters inspired by these datasets[cite: 12].)*

| Dataset / Archive | Planetary Body | How It Is Used in ASTROBASE |
| :--- | :--- | :--- |
| **[LRO Diviner Lunar Radiometer Data](https://www.diviner.ucla.edu/data)** | Moon | Informs the extreme temperature contrast between sunlit polar ridges and permanently shadowed cold traps (`-175 °C`)[cite: 12]. |
| **[NASA SVS 4574 — Lunar South Pole Illumination](https://svs.gsfc.nasa.gov/4574/)** & **[LPI Lunar South Pole Atlas](https://www.lpi.usra.edu/lunar/lunar-south-pole-atlas/)** | Moon | Guides the lunar south pole terrain model, low-angle sunlight cycles, and water-ice discovery mechanics[cite: 12]. |
| **[NASA PDS Curiosity MSL REMS Dataset](https://pds.nasa.gov/ds-view/pds/viewProfile.jsp?dsid=MSL-M-REMS-4-ENVRDR-V1.0)** | Mars | Provides historical Martian surface temperature and atmospheric pressure ranges used to model daily thermal swings[cite: 12]. |
| **[Mars 2020 Perseverance Instruments (MEDA & MOXIE)](https://science.nasa.gov/mission/mars-2020-perseverance/science-instruments/)** | Mars | Models Jezero Crater dust haze, solar panel dust attenuation, and $\text{CO}_2$-to-$\text{O}_2$ oxygen generation[cite: 12]. |
| **[NASA DONKI (Space Weather Database)](https://ccmc.gsfc.nasa.gov/tools/DONKI/)** | Sun / Space Weather | Models C-, M-, and X-class solar flare classifications, radiation hazard alerts, and regolith shielding mechanics[cite: 12]. |

---

## 🛠️ Tech Stack & Project Structure
* **Frontend & UI:** HTML5, CSS3, Vanilla JavaScript (ES6+)[cite: 12]
* **3D Graphics Engine:** [Three.js (r128)](https://threejs.org/) & `OrbitControls`[cite: 12]
* **Data Persistence:** Browser `localStorage` for saving mission state, achievements, and quiz progress offline[cite: 12]
* **Hosting:** Netlify 

```text
AstroBase-NasaSpaceAppsChallenge2026/
├── index.html          # Self-contained web application (3D terrain engine, simulation loop, Space Academy, and Quiz Center)
└── README.md           # Project overview, educational features, dataset citations, and local setup instructions
