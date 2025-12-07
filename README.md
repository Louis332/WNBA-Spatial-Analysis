# WNBA-Spatial-Analysis
# WNBA Spatial Analysis: Ghost Defense Tracker 🏀

## 🎯 Project Overview
This project leverages **Python** and **Spatial Analytics** to visualize defensive control in real-time. By applying **Voronoi Tessellation** to tracking data, we can identify "Ghost Defense" (uncovered spaces) and evaluate defensive spacing efficiency.

## 📺 Demo: Real-Time Spacing
![WNBA Animation](wnba_ghost_defense.gif)
*(Above: A simulation of 10 players where defensive zones (Grey) and offensive zones (Orange) adjust dynamically)*

## 🛠️ Tech Stack
* **Python**: Core logic & Simulation.
* **Scipy (Spatial)**: Computing Voronoi regions.
* **Matplotlib**: Rendering and frame-by-frame animation.
* **Pandas**: Data structuring.

## 🚀 How it works
1. **Simulation**: Generates realistic player trajectories (interpolation).
2. **Modeling**: Calculates the nearest neighbor for every point on the court.
3. **Visualization**: Highlights areas controlled by the defense vs offense.

---
*Project created by Louis Depoortère for WNBA Data Application.*
