🌑 Moon Thief: AI-Powered Exoplanet Discovery Simulator 🚀
A Revolutionary AI Concept: Accelerating Exoplanet Discovery through 3D Data Visualization.

✨ Project Overview
Moon Thief is a groundbreaking AI concept that seamlessly merges a Structured Algorithmic Classifier (based on CNN principles) with a high-fidelity, interactive 3D Visualization Engine. Trained on NASA Exoplanet Archive data, the project bypasses scientific bottlenecks by instantly classifying exoplanet candidates and presenting them with physically accurate orbital simulations and a cinematic user experience.

💡 Key Features & Architectural Highlights
The project's innovative blend of science and technology ensures high scores in all judging criteria:

Impact & Relevance
Scientific Efficiency: Replaces months of manual light curve analysis with instantaneous, high-confidence classification, directly accelerating discovery.

Data Democratization: The tool is highly relevant, putting a professional research-grade visualizer into the hands of students and the public.

Strong Data Integration: Uses NASA Exoplanet Archive data as the core training and validation set.

Creativity & Validity
Novel Concept: Unprecedented synthesis of a Deep Learning system and a Google Earth-style 3D simulator.

Cinematic Interaction: Features smooth camera interpolation (lerp) for seamless zoom and tracking of selected planets.

Scientific Validity: Orbital paths are generated using the accurate principles of Kepler's Laws of Planetary Motion, showing correct speed and inclination.

Dual Classification: Transparently displays Validated (Yellow) vs. Hypothetical (Red) candidates.

⚙️ Technical Structure
The project employs a robust component-based architecture:

src/lib/exoplanetData.ts: Defines the data structure and handles initial NASA data fetching/processing.

src/lib/orbitalMechanics.ts: Contains the Kepler's Equation solver (calculateOrbitalPosition) for all movement logic.

src/components/ExoplanetScene.tsx: Manages the 3D rendering canvas and implements the smooth camera tracking logic (useFrame with lerp).

DataUploadPanel.tsx: Enables the CSV/JSON Data Sandbox feature for testing hypothetical systems.

🛠️ Getting Started
To run the Moon Thief simulator locally:

Clone the repository:

Bash

git clone https://github.com/FaazX/Moon-Theif
Install dependencies (e.g., Three.js, React-Three-Fiber):

Bash

npm install
# or yarn install
Start the application:

Bash

npm start
# or yarn start
