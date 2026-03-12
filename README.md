# CO 543 - Machine Exercise 1: Red Light Green Light

**Author:** Alwyn John Batu

This repository contains a web-based implementation of the "Red Light Green Light" game. It captures real-time webcam frames to detect movement and run a state-based game logic pipeline.

## 🎥 Demo Video
**https://youtu.be/dkSxGfGUEoo**

## Files Included
* `rlgl.html`: The web application source code containing the UI, frame preprocessing, and state machine logic.
* `CO543-ME1.pdf`: A short report detailing the algorithm design, parameter tuning, and observed failure cases.
* `README.md`: This document, containing the project overview and demonstration link.

## How to Run
1. Download or clone this repository.
2. Open the `rlgl.html` file in any modern web browser (e.g., Chrome, Edge, Safari).
3. Grant the browser permission to access your webcam when prompted.
4. Click the **Start Game** button to begin.

## Technologies Used
* **HTML5 / CSS3:** For the user interface and visual state feedback.
* **Vanilla JavaScript:** For the core game loop, timers, and state machine.
* **HTML5 Canvas & WebRTC API:** For continuous webcam streaming and pixel-level motion detection.
