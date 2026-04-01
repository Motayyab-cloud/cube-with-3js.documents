HCI Lab 5B – Three.js Colored Cube
📌 Overview

This lab introduces Three.js in a React environment and demonstrates how to create and animate a 3D cube. The focus is on understanding scenes, cameras, renderers, and materials, with emphasis on human-computer interaction principles like visual clarity and feedback.

🎯 Objectives
Integrate Three.js into a React project
Understand core 3D components: Scene, Camera, Renderer
Create a cube with different colors on each face
Implement smooth rotation animation
Learn clean React integration using hooks (useEffect, useRef)
⚙️ Features
3D Scene Setup – All objects live in a THREE.Scene
Perspective Camera – Defines viewing angle and depth
WebGL Renderer – Displays the scene in the browser
Multi-Colored Cube – Each face can have a unique color
Animation Loop – Smooth rotation using requestAnimationFrame
Resource Cleanup – Removes renderer and disposes resources on unmount
🧩 Key Concepts
THREE.Scene() → Container for all 3D objects
THREE.PerspectiveCamera() → Viewing perspective
THREE.WebGLRenderer() → Renders the scene
THREE.BoxGeometry() → Defines cube shape
THREE.MeshBasicMaterial() → Assigns color/material per cube face
requestAnimationFrame() → Smooth animation loop
React Hooks:
useEffect → Lifecycle management
useRef → DOM mounting point
📁 Project Structure
Cube.js → Contains the Three.js cube setup and animation
App.js → Renders the Cube component
🚀 Outcome
Learn to render 3D graphics in the browser
Integrate Three.js with React efficiently
Apply HCI principles for visual clarity (different cube face colors, smooth rotation)
Prepare for building more interactive 3D applications, like games or simulations
---

## 📌 Conclusion

This lab successfully demonstrates the basics of Three.js by creating and animating a 3D cube. It reinforces the understanding of core 3D concepts and provides hands-on experience in combining modern frontend tools with 3D rendering.

---
