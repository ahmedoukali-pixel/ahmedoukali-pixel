<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="header.svg" width="100%" alt="Ahmed Oukali"/>

<img src="orbit.svg" width="260" alt="AO orbit"/>

<a href="https://github.com/ahmedoukali-pixel">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=2C9FB7&center=true&vCenter=true&multiline=false&width=900&height=50&lines=Custom+sensor+hardware+%E2%86%92+firmware+%E2%86%92+AI;Embedded+Systems+%7C+Edge+AI+%7C+Industrial+Automation;Multi-depth+soil+sensing+%26+smart+irrigation;Environmental+Sensing+%7C+Precision+Agriculture+%7C+PCB+Design" alt="Typing SVG"/>
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=ahmedoukali-pixel&label=Profile%20views&color=2C9FB7&style=for-the-badge" alt="views"/>
<img src="https://img.shields.io/badge/Status-Open%20to%20collaborate-2ea44f?style=for-the-badge&logo=statuspage&logoColor=white" alt="status"/>
<img src="https://img.shields.io/badge/Tiaret%2C%20Algeria-2C5364?style=for-the-badge&logo=googlemaps&logoColor=white" alt="location"/>

<br/><br/>

<a href="https://github.com/ahmedoukali-pixel"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/oukali-ahmed/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ahmed.oukali.eng@gmail.com"><img src="https://img.shields.io/badge/Email-c14438?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

<br/>

<!-- ===================== ABOUT ===================== -->
## 👋 About Me

I'm **Ahmed**, an **Embedded Systems & Electronics Engineer** with an **M.Sc. in Embedded Systems Engineering** from **Ibn Khaldoun University of Tiaret, Algeria**.

I build systems where **the physical world meets software**: custom sensors, low-level firmware, signal processing, and AI that turns raw measurements into decisions, plus the databases and dashboards that make that data usable.

<div align="center">

| | |
|:--|:--|
| 🎓 **Education** | M.Sc. Embedded Systems Engineering, Université Ibn Khaldoun de Tiaret (2024–2025), ranked 1st in Electronics |
| 💼 **Now** | Industrial automation (PLC / HMI / SCADA) at **Tassyir Digital** |
| 🧠 **Previously** | AI Intern at **SIINE Academy** |
| 🔭 **Focus** | Environmental sensing · Edge AI · Precision agriculture · Digital twins |
| 🌍 **Languages** | Arabic (native) · English · French |

<img src="pipeline.svg" width="100%" alt="Electronics → Sensors → Firmware → Signal Processing → AI/ML → Automation"/>

<br/>

<img src="terminal.svg" width="720" alt="Animated terminal"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="3"/>

<!-- ===================== WHAT I DO ===================== -->
## 🧭 What I Do

<div align="center">

| 🔌 Sense | ⚙️ Process | 🧠 Decide |
|:--|:--|:--|
| Custom sensor probes | Low-level firmware (C / C++) | KNN and MLP models |
| Analog signal conditioning | Filtering and signal processing | Edge AI and on-device inference |
| Multi-layer PCB design | SQL / SQLite logging | Irrigation and lighting control |
| Proteus 8.17 · Ngspice simulation | MQTT and wireless links | Dashboards and PLC / SCADA automation |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="3"/>

<!-- ===================== FEATURED ===================== -->
## 🌱 Featured Project

### Real-Time Monitoring and Autonomous Smart Irrigation Based on Soil Moisture Profiling

An **IoT + Edge AI agricultural system** that builds a **vertical soil profile**, so irrigation decisions reflect the **root zone** instead of a single surface value.

```mermaid
flowchart LR
    A[🌱 Soil] --> B[Multi-depth probe<br/>capacitive + temperature]
    B --> C[Signal conditioning<br/>& filtering]
    C --> D[Sensor validation<br/>across nodes]
    D --> E[KNN / MLP]
    E --> F[💧 Irrigation decision]
    E --> G[📊 Dashboard + SQLite log]
```

| Capability | Details |
|:--|:--|
| 🧪 **Custom probe** | Helical capacitive moisture electrodes with temperature sensing at several depths |
| 📉 **Signal conditioning** | TLV272-based analog stage, temperature-assisted interpretation |
| 🧠 **Intelligence** | KNN and MLP, tested on black, red and brown soils over ~2 months |
| 🕸️ **Local network** | Nodes cross-check neighbors to flag abnormal or failed sensors, no cloud dependency |
| 🗄️ **Data logging** | SQL / SQLite storage of readings and decisions |
| 📊 **Visualization** | Dashboard with the soil profile (roadmap: Raspberry Pi hub) |
| 🌍 **Impact** | Designed for water optimization in semi-arid agriculture |

<details>
<summary><b>🏗️ System architecture, layer by layer</b></summary>
<br/>

| Layer | Role | Technologies |
|:--|:--|:--|
| **1. Sensing** | Capacitive moisture and temperature at multiple depths | Custom helical electrodes |
| **2. Conditioning** | Amplification, filtering, temperature compensation | TLV272 · Proteus 8.17 · Ngspice |
| **3. Node firmware** | Acquisition, calibration, packet handling | C · PIC (current) → STM32 (roadmap) |
| **4. Validation** | Neighbor cross-check to detect failed or abnormal sensors | Local network logic |
| **5. Intelligence** | Soil-state classification and irrigation decision | KNN · MLP · Python |
| **6. Hub & interface** | Storage, dashboard, optional camera | SQLite · Raspberry Pi · nRF24L01 · WebSocket / FastAPI |

</details>

<img src="https://img.shields.io/badge/TRL--4-Laboratory%20proof--of--concept-orange?style=flat-square"/>

> Roadmap items (STM32 nodes, nRF links, Raspberry Pi hub with dashboard, AI and camera) are planned, not deployed.

<table>
  <tr>
    <td align="center"><img src="pcb-top.png" alt="PCB top view"/><br/><sub>Board layout, 3D view</sub></td>
    <td align="center"><img src="pcb-chip.png" alt="PCB with microcontroller"/><br/><sub>Microcontroller board, 3D view</sub></td>
  </tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="3"/>

<!-- ===================== SECOND PROJECT ===================== -->
## 💡 Embedded AI Project

### Smart Lighting Control System

AI-based **remote lighting control** with energy optimization, from ESP32 firmware to a mobile app.

```mermaid
flowchart LR
    A[ESP32 node] -->|WiFi / BLE| B[MQTT]
    B --> C[Cloud API]
    C --> D[TensorFlow model]
    D --> E[💡 Lighting control]
    C --> F[📱 React Native app]
```

- 📡 Connectivity over **WiFi / BLE** and **MQTT**
- 🧠 **TensorFlow** model for energy optimization
- 📱 Mobile control through a **React Native** app
- 🔗 [Source code](https://github.com/ahmedoukali-pixel/lighting-control)

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="3"/>

<!-- ===================== RESEARCH ===================== -->
## 💳 AI Research Project

### Enhancing Fraud Detection Through Synthetic Tabular Data Augmentation

Improving **financial fraud detection** with synthetic data generation and machine learning on the **IEEE-CIS Fraud Detection** dataset.

```mermaid
flowchart LR
    A[IEEE-CIS Dataset] --> B[Preprocessing]
    B --> C[Class Imbalance]
    C --> D[SMOTE / ADASYN]
    C --> E[CTGAN]
    D --> F[ML Models]
    E --> F
    F --> G[Fraud Detection]
    G --> H[PR-AUC · ROC-AUC · F1]
```

- ⚖️ Severe class imbalance analysis
- 🔄 Oversampling with **SMOTE** and **ADASYN**
- 🧬 Synthetic tabular generation with **CTGAN**
- 📊 Evaluation with **PR-AUC, ROC-AUC, Precision, Recall, F1**
- 🔬 Comparative study of augmentation strategies

> Academic / team work. My contribution: _fill in your part here_.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="3"/>

<!-- ===================== PROJECTS ===================== -->
## 🛠️ Projects

### 🔧 Embedded & Hardware

| Project | What it does | Stack | Links |
|:--|:--|:--|:--|
| 🌱 **Soil Moisture Profiling** | Multi-depth soil sensing and autonomous irrigation | Custom probe · TLV272 · PIC · KNN · MLP · SQLite | [GitHub](https://github.com/ahmedoukali-pixel) |
| 💡 **Smart Lighting Control** | AI-based remote lighting control with energy optimization | ESP32 · TensorFlow · WiFi/BLE · MQTT · React Native | [Code](https://github.com/ahmedoukali-pixel/lighting-control) |
| 🤖 **Autonomous Robot with AI Vision** | Object detection and navigation | ESP32 · TensorFlow Lite · OpenCV | [Code](https://github.com/ahmedoukali-pixel/autonomous-robot) |
| 🔌 **Multi-Layer PCB Design** | Signal-integrity and thermal optimization | Altium Designer · Proteus 8.17 | See hardware images above |

### 🌐 Software, Data & Team Projects

| Project | What it does | Stack | Links |
|:--|:--|:--|:--|
| 🌾 **AgriTwin** | Real-time agricultural monitoring and intelligent irrigation (team project) | Raspberry Pi · NRF24L01 · FastAPI · WebSocket · AI | [Repository](https://github.com/hostinghosting144-star) |
| 🗺️ **Digital Twin for Agricultural Monitoring** | Digital twin of a monitored agricultural site | IoT data · simulation | Academic work |
| 📦 **E-commerce Warehouse Simulation** | Warehouse management simulation | AnyLogic | Academic work |
| 💳 **Fraud Detection** | Fraud classification with synthetic tabular data augmentation | Python · XGBoost · Random Forest · SMOTE · CTGAN | [Repository](https://github.com/hostinghosting144-star) |
| 🎓 **Wonder School** | Online education and school management platform | Vue 3 · Vite · Tailwind · FastAPI · PostgreSQL | [Repository](https://github.com/hostinghosting144-star) |
| 🧠 **Recommendation System** | Personalized recommendations via collaborative filtering | Java · JavaFX · Cosine Similarity | [Repository](https://github.com/hostinghosting144-star) |
| 🎮 **MAZE GARDEN** | Interactive web platform for games and puzzles | HTML5 · CSS3 · JavaScript | [Live](https://hostinghosting144-star.github.io/MAZE_GARDEN./) · [Source](https://github.com/hostinghosting144-star/MAZE_GARDEN) |
| 🌐 **Portfolio** | Animated, responsive portfolio site (dark theme, scroll animations) | HTML5 · CSS3 · JavaScript | [Live](https://hostinghosting144-star.github.io/Portfolio/) |

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="3"/>

<!-- ===================== TECH STACK ===================== -->
## ⚡ Tech Stack

<div align="center">

**🔧 Embedded Systems**<br/>
<img src="https://skillicons.dev/icons?i=c,cpp,arduino,raspberrypi,linux&perline=5" /><br/>
<sub>PIC16F/18F · dsPIC33 · STM32 · ESP32 · FreeRTOS · MPLAB X · Keil µVision</sub>

<br/><br/>

**🔌 Hardware, Simulation & Signal**<br/>
<img src="https://img.shields.io/badge/Proteus-8.17-1B6AC9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Altium%20Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white"/>
<img src="https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white"/>
<img src="https://img.shields.io/badge/Ngspice-555555?style=for-the-badge"/><br/>
<sub>Analog signal conditioning · Multi-layer PCB · DSP · Circuit simulation</sub>

<br/><br/>

**🧠 AI & Vision**<br/>
<img src="https://skillicons.dev/icons?i=python,tensorflow,opencv,matlab&perline=4" /><br/>
<sub>KNN · MLP · TensorFlow Lite · Edge AI · On-device inference</sub>

<br/><br/>

**🗄️ Data & Databases**<br/>
<img src="https://skillicons.dev/icons?i=sqlite,fastapi&perline=2" /><br/>
<sub>SQL (queries, schema design, joins) · SQLite · MQTT · WebSocket · Local dashboards</sub>

<br/><br/>

**🎨 Web & Mobile**<br/>
<img src="https://skillicons.dev/icons?i=html,css,js,react&perline=4" /><br/>
<sub>Responsive design · CSS animations · Intersection Observer · React Native</sub>

<br/><br/>

**📝 Research & Documentation**<br/>
<img src="https://skillicons.dev/icons?i=latex&perline=1" /><br/>
<img src="https://img.shields.io/badge/Overleaf-47A141?style=for-the-badge&logo=overleaf&logoColor=white"/><br/>
<sub>Scientific writing, reports and papers in LaTeX</sub>

<br/><br/>

**🏭 Industrial & Tools**<br/>
<img src="https://skillicons.dev/icons?i=git,github,vscode&perline=3" /><br/>
<sub>PLC · HMI · SCADA</sub>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="3"/>

<!-- ===================== EXPERIENCE ===================== -->
## 🏆 Experience

<div align="center">

| Role | Organization | Period |
|:--|:--|:--|
| 🏭 **Industrial Automation (PLC / HMI / SCADA)** | Tassyir Digital | Apr 2026 – Present |
| 🤖 **Artificial Intelligence Intern** | SIINE Academy | Jan 2026 – Apr 2026 |

</div>

<details>
<summary><b>📚 Research & Academic Work</b></summary>
<br/>

- Real-Time Monitoring and Autonomous Smart Irrigation Based on Soil Moisture Profiling
- Fraud Detection Through Synthetic Tabular Data Augmentation
- Digital Twin for Agricultural Monitoring
- E-commerce Warehouse Management Simulation (AnyLogic)
- Machine Learning & Data Science projects
- Web & mobile application development

</details>

<details>
<summary><b>🏅 Competitions</b></summary>
<br/>

| Event | Date | Notes |
|:--|:--|:--|
| Chipathon 2026, Track B: Circuits for Sensors | 2026 | Participant · OpenLane · Sky130 · Magic · Ngspice |
| INV-TECH Hackathon | Mar 2025 | 5G and IoT solutions |
| Drone Innovation Challenge | Sep 2024 | Autonomous drone systems for agriculture and delivery |
| NOVATECH Hackathon | Nov 2023 | **Finalist** |

</details>

<details>
<summary><b>📜 Certificates</b></summary>
<br/>

- Advanced Embedded Systems Design
- Computer Vision for Robotics
- IoT System Architecture
- RTOS Programming (FreeRTOS)
- Advanced PCB Design

</details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="3"/>

<!-- ===================== ROADMAP ===================== -->
## 🚀 What I'm Working On

| Status | Item |
|:--|:--|
| 🔬 **Active** | Soil moisture profiling: validation across soils and sensor-failure detection |
| 🧪 **Next** | Migrating nodes from PIC to STM32 with nRF links |
| 🖥️ **Next** | Raspberry Pi hub: dashboard, AI inference and camera |
| 🎯 **2026** | Chipathon 2026, Track B: analog circuits for sensors (Sky130) |

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="3"/>

<!-- ===================== STATS ===================== -->
## 📊 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=ahmedoukali-pixel&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true&border_radius=12"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ahmedoukali-pixel&layout=compact&theme=tokyonight&hide_border=true&border_radius=12"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ahmedoukali-pixel&theme=tokyonight&hide_border=true&border_radius=12"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ahmedoukali-pixel&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Activity" width="100%"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ahmedoukali-pixel/ahmedoukali-pixel/output/github-snake-dark.svg"/>
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/ahmedoukali-pixel/ahmedoukali-pixel/output/github-snake.svg" width="100%"/>
</picture>

<img src="https://github-profile-trophy.vercel.app/?username=ahmedoukali-pixel&theme=tokyonight&no-frame=true&no-bg=true&margin-w=12&row=1&column=6"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="3"/>

<!-- ===================== AREAS ===================== -->
## 🎯 Areas of Interest

<div align="center">

<img src="https://img.shields.io/badge/Embedded%20Systems-0f2027?style=for-the-badge&logo=microchip&logoColor=white"/>
<img src="https://img.shields.io/badge/Edge%20AI-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Environmental%20Sensing-2C9FB7?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Precision%20Agriculture-2ea44f?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Digital%20Twins-203a43?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Industrial%20Automation-203a43?style=for-the-badge"/>
<img src="https://img.shields.io/badge/PCB%20Design-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL%20%26%20Data-4479A1?style=for-the-badge&logo=sqlite&logoColor=white"/>

</div>

<!-- ===================== CONTACT ===================== -->
## 🤝 Let's Build Something

Open to collaboration on **embedded systems, environmental sensing, Edge AI, smart agriculture, digital twins** and technical web platforms.

<div align="center">

<a href="https://www.linkedin.com/in/oukali-ahmed/">
  <img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:ahmed.oukali.eng@gmail.com">
  <img src="https://img.shields.io/badge/Send%20an%20Email-c14438?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3500&pause=1500&color=2C9FB7&center=true&vCenter=true&width=700&lines=%22Innovating+the+future%2C+one+circuit+at+a+time.%22" alt="quote"/>

<img src="footer.svg" width="100%" alt="footer"/>

</div>
