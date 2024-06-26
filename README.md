# 3D Earth Globe with ISS Tracking

This project utilizes Three.js to create a 3D representation of Earth with real-time tracking of the International Space Station (ISS). The ISS position is fetched from the [Where the ISS at?](https://wheretheiss.at/) API and displayed on the globe in real-time.

![Demo](demo.gif)

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [How to Use](#how-to-use)
- [Credits](#credits)
- [License](#license)

## Features

- Real-time visualization of the Earth using a textured 3D sphere.
- Continuous rotation of the Earth for a dynamic viewing experience.
- Real-time tracking and display of the ISS position on the globe.
- Uses fetch API to get ISS coordinates from a third-party API.
- Responsive design suitable for desktop and mobile devices.

## Technologies Used

- [Three.js](https://threejs.org/) - JavaScript library used for WebGL 3D graphics rendering.
- [OrbitControls.js](https://threejs.org/docs/#examples/en/controls/OrbitControls) - Controls to orbit around a target.
- [Where the ISS at? API](https://wheretheiss.at/) - API providing real-time ISS location data.

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/connorgladish/ISS-Tracking.git
   
2. **Navigate into the project directory:**

   ```bash
   cd ISS-Tracking
   
3. **Open the project in your code editor.**

   Run a local development server (e.g., using Python's built-in server):

   ```bash
   python -m http.server

4. **Open the project in your web browser:**

   Open http://localhost:8000 (or another port if specified) in your web browser.

# How to Use #

- Upon loading the webpage, you will see a 3D representation of the Earth with the ISS represented as a small red sphere.
- The Earth rotates continuously for a dynamic effect.
- The ISS position updates approximately every 5 seconds, showing its real-time location.
----
# Credits # 
Earth texture image from NASA.

# License #
This project is licensed under the MIT License - see the LICENSE file for details.
