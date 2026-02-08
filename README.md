## Basic 3D Hand Tracking (Web AR)
A real-time browser-based augmented reality hand tracking system using only a webcam.
The program detects your hand, tracks 21 key points, reconstructs a 3D skeletal model, and overlays it onto your real hand with matching size and position in real time. Everything runs locally in the browser — no downloads required.

___
**How it works**
*MediaPipe detects hand key points from the camera feed
*The 2D coordinates are projected into 3D space
*A 3D hand skeleton is rendered using Three.js
*Depth estimation + smoothing keeps the hand stable and aligned

___
**Tech Stack**
*JavaScript
*Three.js
*MediaPipe Hands
*WebGL

___
**Run locally**

**Clone the repo:**
git clone https://github.com/Bouwles/basic-3d-hand-tracking.git
cd basic-3d-hand-tracking


**Start a local server (camera won’t work if opened as a file):**
python -m http.server 8000


**Then open:**
http://localhost:8000
