3D Solar System Simulation
Overview
This project is a mobile-responsive web page that simulates the solar system in 3D using Three.js. It includes the Sun and eight planets (Mercury to Neptune) with realistic orbits, lighting, and user controls to adjust planet speeds in real-time. Bonus features include a pause/resume button, background stars, planet labels on hover, dark/light theme toggle, and camera movement/zoom.
Features

3D Solar System: Sun at the center with eight planets orbiting at realistic distances and speeds.
Real-time Speed Controls: Sliders for each planet to adjust orbital speed dynamically.
Pause/Resume: Button to pause or resume the animation.
Background Stars: 1000 randomly placed stars for a realistic space effect.
Planet Labels: Tooltips display planet names on hover.
Dark/Light Theme: Toggle between light and dark UI themes.
Camera Controls: Drag to pan the camera and scroll to zoom in/out.
Mobile-Responsive: Adapts to different screen sizes with adjusted control panel layout.

How to Run

Clone or Download: Unzip the project folder.
Open index.html: Use a web server (e.g., python -m http.server or VS Code Live Server) to serve the index.html file, as Three.js requires a server for loading.
View in Browser: Open the served URL in a modern browser (Chrome, Firefox, or Safari recommended).
Interact:
Use sliders in the control panel to adjust planet speeds.
Click "Pause" to stop/resume the animation.
Click "Dark Theme" to toggle the UI theme.
Hover over planets to see their names.
Drag the mouse to pan the camera, and scroll to zoom.



Dependencies

Three.js: Included via CDN (v128). No local installation required.

File Structure

index.html: Main file containing HTML, CSS, and JavaScript for the simulation.
README.md: This file with setup and usage instructions.
(Demo video should be included in the submission zip as demo.mp4)

Notes

The project uses THREE.Clock and requestAnimationFrame for smooth animations.
The scene is optimized for performance with simple sphere geometries and minimal lighting.
Ensure a modern browser with WebGL support for the best experience.
The control panel is styled with CSS and uses media queries for mobile responsiveness.

Demo Video
The demo video (demo.mp4) showcases:

The 3D solar system with planets orbiting the Sun.
Real-time speed adjustments using sliders.
Explanation of planet and orbit creation (using Three.js spheres, positions, and animation loop).
Code walkthrough with voice narration, highlighting key components like scene setup, controls, and bonus features.

