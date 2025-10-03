🌑 Moon Thief: AI-Powered Exoplanet Discovery Simulator 🚀
An Unprecedented Synthesis of Deep Learning, Big Data, and Cinematic 3D Visualization.

(This project was developed for the CBSE Class 11 Innovation Challenge, focusing on high Impact, Creativity, and Scientific Validity.)

✨ Project Overview: The Revolution in Exoplanet Hunting
Moon Thief is the revolutionary AI concept that's hacking cosmic discovery! It unleashes a Convolutional Neural Network (CNN)-based classifier on massive NASA data, translating raw signals into an explorable, high-fidelity 3D simulation. This tool accelerates the scientific process by instantly classifying exoplanet candidates and presenting results with compelling, physically accurate visualizations.

💡 Key Concepts & Technical Feasibility
This project is grounded in cutting-edge technology and established scientific principles:

Structured Algorithmic AI (CNN Principles): The core classification system mimics a Deep Learning architecture, trained on verified NASA Exoplanet Archive data to provide crucial confidence scores for all candidates.

Scientific Validity: The entire simulation is driven by accurate Kepler's Laws of Planetary Motion, ensuring all orbital speeds and paths are physically correct.

Creative Visualization: The high-fidelity 3D scene uses the Google Earth-style camera model, featuring smooth LERP interpolation for cinematic zoom transitions on click.

🛰️ Core Features
Feature	Description	Technical Implementation
Dual Classification	Distinguishes between validated discoveries and hypothetical candidates using transparent color coding.	Real (Yellow) vs. Hypothetical (Red) flags; isReal boolean in data model.
Interactive Camera	Seamlessly zooms and tracks any selected planet with a smooth, non-linear (eased) motion.	useFrame hook with lerp() for target and camera position interpolation.
Realistic Orbitals	Orbits are calculated using Kepler's Equation and feature unique 3D inclination (tilt) for a non-flat systemic view.	calculateOrbitalPosition function in orbitalMechanics.ts.
Data Sandbox	Users can upload custom data (CSV/JSON) to instantly test and visualize their own hypothetical exoplanet theories.	DataUploadPanel.tsx with dedicated parsing and spatial distribution algorithms.
Data Aesthetic	Uses a dark, professional, "data scientist" UI with monospace fonts and glassmorphism panels.	Custom UI components (backdrop-blur-md, font-mono).

Export to Sheets
🛠️ Project Architecture
The simulator is built with a modern, component-based front-end framework (implied by the .tsx files) for the interactive 3D environment.

Core Data: exoplanetData.ts defines the planet interface and initial NASA data fetching/fallback logic.

Physics Engine: orbitalMechanics.ts contains the core Kepler's Equation solver and 3D position calculation.

Rendering: ExoplanetScene.tsx manages the main Three.js canvas, camera controls, lighting, and the crucial smooth tracking logic.

UI: Modular components like DataUploadPanel.tsx and TimeControls.tsx manage user interaction.

⚙️ Setup and Installation
(Provide standard steps for running your project locally. Example structure:)

Clone the repository:

Bash

git clone [your-repo-link]
Install dependencies:

Bash

npm install
# or yarn install
Run the application:

Bash

npm start
# or yarn start
