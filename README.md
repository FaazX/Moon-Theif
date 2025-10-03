-----

# 🌑 Moon Thief

**A Revolutionary AI Concept: Accelerating Exoplanet Discovery through 3D Data Visualization.**

-----

## ✨ Project Overview

**Moon Thief** is the revolutionary AI concept that's hacking cosmic discovery\! It seamlessly merges a **Structured Algorithmic Classifier** (based on **CNN** principles) with a high-fidelity, interactive **3D Visualization Engine**. Trained on **NASA Exoplanet Archive** data, the project bypasses scientific bottlenecks by instantly classifying exoplanet candidates and presenting them with compelling, **physically accurate orbital simulations** and a **cinematic user experience**.

-----

## 💡 Judging Criteria Success Summary

This project is built to score high on all criteria, proving exceptional value and rigor:

| Criteria |Moon Theif's integration|
| :--- | :--- |
| **IMPACT** | Annihilates the **data bottleneck** in astrophysics, instantly accelerating discovery, and democratizing access to professional science tools. |
| **CREATIVITY** | The **Novel Concept** of synthesizing a **Deep Learning** system with a **Google Earth-style 3D simulator** and **cinematic LERP zoom**. |
| **VALIDITY** | Grounded in **Kepler's Laws of Planetary Motion** and uses **NASA data** as its core source, ensuring scientific and technical feasibility. |
| **RELEVANCE** | Sits at the intersection of **Deep Learning, Big Data, and Space Exploration**, providing a highly relevant prototype for future scientific visualization. |

-----

## 🛰️ Core Features & Technical Implementation

| Feature | Description | Technical Implementation |
| :--- | :--- | :--- |
| **Interactive Camera** | Smoothly tracks any selected planet with a gentle, non-linear (cinematic) motion. | `useFrame` hook with **LERP** (linear interpolation). |
| **Realistic Orbitals** | Orbits calculated using **Kepler's Equation**, showing correct speed and inclination. | `orbitalMechanics.ts` (Physics Engine). |
| **Data Sandbox** | Users upload custom data (CSV/JSON) to instantly test hypothetical theories. | `DataUploadPanel.tsx` with dedicated parsing logic. |
| **Dual Classification** | Transparently separates validated data (Yellow) from user candidates (Red) via AI confidence scoring. | `isReal` boolean + confidence score logic. |

-----

## ⚙️ Project Architecture

The project employs a robust, component-based structure:

1.  **`src/lib/orbitalMechanics.ts`**: Contains the core **Kepler's Equation solver** for all physics and movement.
2.  **`src/lib/exoplanetData.ts`**: Defines the data model and handles NASA data integration.
3.  **`src/components/ExoplanetScene.tsx`**: Manages the 3D rendering, camera controls, and smooth object tracking.
4.  **`DataUploadPanel.tsx`**: Manages user interaction and data ingestion.

-----

## 🛠️ Getting Started

To run the Moon Thief simulator locally:

1.  **Clone the repository:**
    ```bash
    git clone (https://github.com/FaazX/Moon-Theif)
    ```
2.  **Install dependencies (e.g., Three.js, React-Three-Fiber, etc.):**
    ```bash
    npm install
    # or yarn install
    ```
3.  **Start the application:**
    ```bash
    npm start
    # or yarn start
    ```

-----

## **© 2025 [Your Name/Team Name] | CBSE Class 11 Innovation Project**
