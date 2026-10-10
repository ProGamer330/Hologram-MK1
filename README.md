# Cosmic Gesture Lab — 3D Particle Playground

I created **Cosmic Gesture Lab**, an interactive 3D particle playground where glowing particles smoothly transform into different forms. I built it to explore real-time particle effects, colors, motion, and optional webcam-based hand controls in a browser.

## Features

- **8 particle forms:** Cosmic Orb, Heart, Flower, Saturn, Fireworks, Galaxy, DNA Helix, and Butterfly.
- **Mouse-controlled form selection:** Click a form in the left panel to morph the particles into it. Form selection does not require hand gestures.
- **Interactive 3D scene:** Drag to rotate the view and scroll to zoom.
- **Particle controls:** Adjust scale and energy using the sliders.
- **Color controls:** Choose a core color, randomize it, or enable automatic color cycling.
- **Ambient sparkle:** Turn the background star field on or off.
- **Animation controls:** Pause or resume the animation, reset the scene, or enter fullscreen.
- **Optional hand tracking:** Enable the camera to control particle expansion, rotation, and hue with hand movement. Pinching does not switch forms; use the mouse buttons instead.

## How to run it

1. Download or save `cosmic_gesture_particles_mouse_control.html`.
2. Open the HTML file in a modern browser such as Google Chrome or Microsoft Edge.
3. Keep an internet connection available. The page loads Three.js and MediaPipe Hands from public CDNs.
4. Use the controls in the left panel and interact with the 3D particle scene.

You can use the main particle playground with your mouse without enabling the camera.

## How to use the controls

### Change the particle form

Click any of the eight form buttons under **Choose a form**. The selected button is highlighted, and the particles smoothly morph into the chosen shape.

### Rotate and zoom

- **Rotate:** Click and drag on the 3D scene.
- **Zoom:** Scroll the mouse wheel over the 3D scene.

### Adjust particles and colors

- **Expansion / scale:** Move the slider to make the form smaller or larger.
- **Particle energy:** Move the slider to adjust the particle glow and movement intensity.
- **Core color:** Click the color swatch to choose a color.
- **Randomize:** Generate a random core color.
- **Automatic color cycling:** Toggle continuous color changes on or off.
- **Ambient sparkle:** Toggle the background star field.

### Other buttons

- **Pause / resume:** Use the pause button near the top-right of the scene.
- **Fullscreen:** Expand the scene to fullscreen.
- **Reset scene:** Restore the default form and main settings.

### Optional webcam hand tracking

1. Click **Enable hand tracking** in the left panel.
2. Approve the browser's camera permission.
3. Show one hand in the camera preview.

Hand controls:

- **Open palm:** Expand the particles.
- **Fist:** Pull the form inward.
- **Move your hand / index finger:** Affect the scene's rotation and particle hue.
- **Change forms:** Click a form button with your mouse. Pinch gestures do not change the form.

Camera access may require a secure browser context. If the camera cannot start when opening the file directly, serve the HTML from `localhost` or a trusted HTTPS site. Hand tracking is optional; mouse controls still work without it.

## Technologies used

- HTML and CSS for the interface
- JavaScript for interaction and animation
- [Three.js](https://threejs.org/) for the 3D particle scene
- [MediaPipe Hands](https://developers.google.com/mediapipe) for optional hand tracking

## Notes

- The app runs in the browser; no separate installation is required.
- An internet connection is needed to load the external libraries.
- The webcam is only requested after clicking **Enable hand tracking**. In this demo, hand landmarks are processed in the browser and the video is not uploaded by the app.
- This project is a learning and creative experiment. Browser performance depends on your device and graphics hardware.

---

**Made by Pro Gamer 330 X**  
*Cosmic Gesture Lab — create, morph, and explore with particles.*
