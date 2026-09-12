# CyberCatsCradleX 🐈‍⬛⚡

CyberCatsCradleX is an interactive cyberpunk web application that transforms traditional hand gestures into a futuristic visual experience. Using real-time hand tracking through the webcam, users can interact with glowing cybernetic hand models, energy strings, particle effects, lasers, shields, and dynamic audiovisual effects.

The application combines creative coding, computer vision, physics-inspired animation, and immersive interface design to create a unique browser-based interactive experience.

<img width="1920" height="971" alt="Screenshot (351)" src="https://github.com/user-attachments/assets/c5720931-cdbf-4b80-9b58-7f649d9ff507" />


## ✨ Features

* **Real-Time Hand Tracking:** Detects and tracks up to two hands using MediaPipe Hands.
* **Gesture Recognition:** Recognizes gestures such as:

  * Open Palm
  * Fist
  * Pinch
  * Point
  * Peace
  * Finger Gun
  * Thumbs Up
  * OK Sign
* **Cybernetic Hand Visualization:** Renders colorful hand skeletons, joints, auras, and animated highlights.
* **Interactive Cat's Cradle:** Connects fingertips from both hands with glowing, elastic, physics-inspired energy strings.
* **Laser Effects:** Pointing gestures trigger futuristic laser beams.
* **Energy Shield:** Open-palm gestures generate a glowing shield effect.
* **Lightning Effects:** Pinch gestures create animated lightning arcs.
* **Particle System:** Includes glowing particles, explosions, shockwaves, and screen effects.
* **Dynamic Cyberpunk Background:** Features digital rain, stars, fog, energy waves, scanlines, and visual grain.
* **Generative Audio:** Produces laser, spark, pulse, and explosion sounds using the Web Audio API.
* **Performance HUD:** Displays FPS, frame time, hand count, particles, strings, tracking quality, and estimated CPU usage.
* **Audio Control:** Includes an audio on/off toggle.
* **Responsive Canvas:** Adjusts the visual stage when the browser window is resized.

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* Canvas API
* [p5.js](https://p5js.org/)
* [MediaPipe Hands](https://chuoling.github.io/mediapipe/solutions/hands.html)
* Web Audio API

## 🚀 How to Run

### Prerequisites

* A modern web browser such as Google Chrome or Microsoft Edge
* A working webcam
* Internet connection for loading the external p5.js and MediaPipe libraries
* Camera permission enabled for the website or local server

### Steps

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Ensure the HTML file is present.
4. Run the application using a local development server.

For example, if you have VS Code with the Live Server extension:

1. Right-click the HTML file.
2. Select **Open with Live Server**.
3. Allow camera access when prompted.
4. Show your hands in front of the webcam and experiment with the supported gestures.

> **Note:** Camera access may be restricted when opening an HTML file directly using `file://`. Running the project through a local server is recommended.

## 🎮 Gesture Interaction

| Gesture                     | Effect                                  |
| --------------------------- | --------------------------------------- |
| Open Palm                   | Displays an energy shield               |
| Fist                        | Triggers a shockwave effect             |
| Pinch                       | Creates a lightning arc                 |
| Point                       | Fires a laser beam                      |
| Two Hands                   | Generates the interactive cat's cradle  |
| Peace / Thumbs Up / OK Sign | Detected and displayed in the interface |

## 📁 Project Structure

```text
CyberCatsCradleX/
│
├── index.html
└── README.md
```

> If the project is later separated into multiple files, CSS and JavaScript can be moved into dedicated folders.

## 🔐 Privacy

The application uses the webcam for real-time hand tracking. The source code is designed to process camera frames in the browser for interaction. Users should review browser camera permissions and understand how the application operates before granting access.

## 🌟 Future Improvements

* Add multiple game modes and challenges
* Introduce a scoring and combo system
* Add customizable cyberpunk themes
* Support mobile-friendly gesture interaction
* Add more gesture-based abilities
* Include offline support by bundling required libraries and models
* Add accessibility controls and keyboard alternatives
* Improve performance on low-end devices

## 📄 License

This project is intended for educational, experimental, and creative purposes. Add an appropriate open-source license if you plan to distribute or modify the project publicly.
