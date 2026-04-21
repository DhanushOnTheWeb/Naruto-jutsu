# ShinobiAR: Mastering the Rasengan and Chidori through Computer Vision

This project is an interactive Naruto vs. Sasuke augmented reality (AR) web application. It uses MediaPipe Hands to detect hand gestures and overlays dynamic "Chidori" and "Rasengan" visual effects (MP4 videos) directly onto your hands in real-time.

# Features

Hand Tracking: Real-time dual-hand detection using MediaPipe.
Gesture Recognition: Detects "Open Palm" to trigger power-up effects.
Dynamic Visuals: * Left Hand: Rasengan (Naruto's effect) appears above the palm.
Right Hand: Chidori (Sasuke's effect) appears at the wrist/knuckle area.
Responsive Power System: Visual effects fade in/out based on how long your hand remains open.
Cyberpunk UI: Features a high-contrast neon blue hand skeleton overlay.

# Getting Started

# 1. Assets Requirement

To make the code work, you need to provide the video assets in the assets/ folder.
Naruto (Rasengan): A circular blue energy video with a black background (for "screen" blend mode).
Sasuke (Chidori): A lightning-style blue energy video with a black background.

# 2. Local Setup

Because this uses camera access and external scripts, it is best run on a local server.
Clone this repository.
Ensure your video files are in the assets/ folder.
Open index.html using a local server (e.g., VS Code "Live Server" extension or Python's http.server).

# 3. How to Use

Allow camera access in your browser.
Left Hand: Open your palm toward the camera to charge the Rasengan.
Right Hand: Open your palm toward the camera to trigger the Chidori.
Close your fist to let the energy dissipate.

# Technical Details

MediaPipe Hands: Used for high-fidelity landmark detection.
Canvas API: Used for drawing the glowing "Bright Blue" hand skeleton.
CSS Mix-Blend-Mode: Set to screen to remove black backgrounds from the MP4 assets, allowing only the glowing energy to be visible over the camera feed.

# License
This project was created for educational and entertainment purposes. Naruto and Sasuke are properties of Masashi Kishimoto/Shueisha.

# Reference for Report Preparation
If you are using this for an internship or academic portfolio, here is the suggested bibliography entry:
MediaPipe Documentation. (2026). Hands: High-fidelity palm detection and hand skeleton tracking. Google Open Source. https://google.github.io/mediapipe/solutions/hands.

live demo : https://dhanushontheweb.github.io/Naruto-jutsu/
