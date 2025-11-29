# Design and Finite Element Analysis of a Rigid Steel Portal Frame 🏗️

![Project Banner](Assets/Assembly)
*An industry-standard portal frame designed in SolidWorks, featuring moment-resisting connections and optimized load paths.*

## 🛠️ Tech Stack
![SolidWorks](https://img.shields.io/badge/CAD-SolidWorks-red)
![FEA](https://img.shields.io/badge/Simulation-Static_Analysis-blue)
![Status](https://img.shields.io/badge/Status-In_Progress-yellow)

## 📖 Project Overview
This project involves the design and structural analysis of a generic industrial warehouse frame. The goal was to move beyond basic geometric modeling and implement **real-world structural detailing** based on industrial standards.

## ⚙️ Key Design Features (The "Why")

### 1. Haunched Eaves Connection
![Haunch Detail](Assets/Hunch)
* **Problem:** The connection between the column and rafter experiences the highest **Bending Moment** in the entire structure.
* **Solution:** Designed a tapered haunch to increase the beam depth at the joint. This significantly reduces stress concentration and allows for a lighter rafter section elsewhere.

### 2. Internal Column Stiffeners (Continuity Plates)
![Stiffener Detail](Assets/Stiffners)
* **Problem:** The compression force from the haunch flange pushes directly against the column web, creating a risk of **Local Web Buckling**.
* **Solution:** Modeled horizontal continuity plates inside the column to bridge the load path and transfer forces effectively.

### 3. Detailed Bolted Assemblies
* Utilized standard structural bolts with appropriate pre-tension clusters in the tension zones.
* Designed flush end-plates for manufacturability.

## 🧪 Simulation & Analysis (FEA)
*Current Status: Setting up Boundary Conditions.*
- **Objective:** Validation of Factor of Safety (FOS) under standard Wind and Roof Live Loads.
- **Assumptions:** Testing rigid (Fixed) vs. pinned base plate scenarios.
- *[Link to Full Simulation Report - Coming Soon]*

## 📂 File Structure
- `CAD_Files/`: Native SolidWorks 2024 files.
- `Universal_Formats/`: STEP files for non-SW users.
- `Drawings/`: 2D Fabrication prints (PDF).

## 👨‍💻 Author
**Karthik V S**
Mechanical Engineering Undergraduate
https://www.linkedin.com/in/karthik-v-s-926b34335
