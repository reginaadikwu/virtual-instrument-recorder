# Virtual Piano & Audio Recorder

An interactive, multimedia web application that features a playable digital instrument keyboard with built-in real-time audio recording, processing, and playback functionality. 

This project was built from scratch using pure frontend technologies to demonstrate an implementation of modern browser audio processing APIs.

## Features
- **Mathematical Audio Synthesis:** Generates high-fidelity sine-wave musical notes in real time using the browser's native Web Audio API.
- **Internal Signal Routing:** Captures the audio stream internally via code destinations rather than utilizing the microphone, resulting in 100% clean, noise-free recordings.
- **Instant Local Playback:** Utilizes media blobs to provide immediate audio rendering and playback controls once recording ceases.
- **Zero Dependencies:** Engineered using strictly vanilla HTML5, CSS3, and JavaScript—meaning no heavy frameworks or downloads are required.

## Project Structure
```text
virtual-instrument-recorder/
├── index.html   (Core application layout, logic, and styling)
└── README.md    (Project documentation)
```

## How to Run the Project Locally
1. Clone or download this repository to your local machine.
2. Open the directory and double-click the `index.html` file.
3. The application will instantly load and run directly inside any modern web browser (Chrome, Edge, Firefox, Safari).

## Tech Stack
- **HTML5:** Semantic architecture and core layout.
- **CSS3:** Responsive visual layout featuring a dark user interface (UI).
- **JavaScript (ES6):** Core engine powered by the `Web Audio API` (for note synthesis) and the `MediaRecorder API` (for audio capturing).
