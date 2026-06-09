Analog Communication Virtual Laboratory Toolkit
An interactive, high-fidelity, web-based virtual laboratory designed for Analog Communication (EC401) engineering curriculum. This project provides an Elite Academic Design Compliance telemetry dashboard to visualize, simulate, and mathematically model various analog modulation schemes in real-time.

Virtual Lab Dashboard Screenshot(Placeholder: Add your screenshot here)

🌟 Features
Elite Telemetry Dashboard: A professional, dark-themed, neon-accented UI that mimics real-world laboratory equipment.
Time-Domain Oscilloscope: High-performance HTML5 Canvas rendering of the message, carrier, and modulated waveforms with custom X/Y Zoom controls.
Frequency-Domain Spectrum Analyzer: Custom stem-plot visualizations accurately depicting carrier and sideband frequencies/powers.
Live Mathematical Modeling: Real-time algebraic formulas (rendered via MathJax) that dynamically substitute variable values as sliders are adjusted.
Academic Telemetry Data: Instantaneous calculation of Modulation Index (μ), Bandwidth, Carrier Power, Sideband Power, Total Power, and Transmission Efficiency.
Zero Dependencies: Built entirely with Vanilla JS, HTML, and CSS. No Node.js, Webpack, or external bundlers required to run.
📡 Modulation Schemes Covered
Currently supports or is architecturally prepared to simulate:

AM (Double Sideband Full Carrier - DSB-FC)
DSB-SC (Double Sideband Suppressed Carrier)
SSB-SC (Single Sideband Suppressed Carrier)
FM (Frequency Modulation)
PM (Phase Modulation)
🚀 How to Run (Local)
Because this project is built using native web technologies, getting it running is frictionless:

Clone or download this repository to your local machine.
Open the project folder.
Double-click on index.html to open it in any modern web browser (Chrome, Firefox, Edge, Safari). (Note: No local server or npm install is required!)
🛠️ Technology Stack
Structure: HTML5
Styling: Vanilla CSS3 (Custom CSS variables, Grid, Flexbox, Neon-glow aesthetics)
Logic & State: Vanilla JavaScript (ES6 Modules/Classes)
Graphics: Native HTML5 <canvas> API (Zero external charting libraries used for maximum performance and customizability)
Mathematics: MathJax via CDN for dynamic LaTeX rendering.
📖 Curriculum Context
This virtual laboratory is specifically tailored to match the syllabus requirements of B.Tech Electronics & Communication Engineering courses (such as MAKAUT EC401). It serves as an interactive study aid to help students visualize complex frequency translations, power distribution, and time-domain envelopes without needing physical hardware.

🤝 Contributing
Contributions, issues, and feature requests are welcome!

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
📝 License
Distributed under the MIT License. See LICENSE for more information.
