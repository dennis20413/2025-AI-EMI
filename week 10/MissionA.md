# DronePaint Reference Guide 📘🚁🎨

## 1. In two sentences, what is DronePaint?
DronePaint is a cutting-edge human-swarm interaction system designed to allow intuitive, device-free control of multiple drones using only hand gestures. By leveraging a Deep Neural Network (DNN)-based gesture recognition module, the system translates human hand motions into drone trajectories, enabling users to create light paintings in mid-air with swarming drones acting as flying pixels of a dynamic, luminous brushstroke.

## 2. How do hand gestures move the drones?
DronePaint relies on a webcam and a computer vision system built with the MediaPipe framework to track 21 key points of the human hand in real time. These points are analyzed using a DNN to classify predefined gestures, such as "thumbs up" or "okay", which are mapped to specific commands like takeoff, drawing, erasing, or landing. Once a gesture is recognized, the system calculates a trajectory based on the hand’s position and movement over time, which is then converted into drone flight instructions using ROS (Robot Operating System) — making your hand the literal joystick of the swarm. 🖐️🧠➡️📈➡️🚁

## 3. What is the system architecture?
DronePaint is built around a three-module software architecture:
- **Human-Swarm Interface**: This module uses MediaPipe for accurate hand tracking and a DNN for gesture recognition. It captures the user's input through a Logitech HD webcam and identifies hand poses and movements in real-time.
- **Trajectory Processing Module**: After a gesture is detected, this module filters and interpolates the path using an alpha-beta filter (α = 0.7). It ensures that the drawn paths are smooth and evenly spaced, suitable for drone flight. The pixel coordinates are then converted into metric-space coordinates for physical deployment.
- **Drone Control System**: The final module uses ROS to communicate trajectory data to the drones. A potential field approach helps manage collision avoidance and navigation by balancing attractive and repulsive forces. Hardware includes Crazyflie 2.0 drones, Vicon motion capture systems, and PCs running Unity for visualization. 🌐📷🧠➡️🛠️📐➡️🚁

## 4. Why do we smooth my hand’s path before flying?
Direct hand gestures tend to produce jagged or uneven trajectories due to natural hand tremors, inconsistent speed, or abrupt changes in motion. If drones were to follow this raw data, flight could become unstable or visually unappealing. The system applies an **alpha-beta filtering algorithm** to reduce noise and smooth the path, followed by linear interpolation to create evenly spaced flight coordinates. This results in safer, more reliable drone navigation and aesthetically pleasing light trails. It's similar to tracing over a rough sketch with a clean marker line before finalizing an artwork. ✍️🔧🪄

## 5. Three simple metaphors for LightPaint?
- **🖌️ Brush in the sky**: Your hand is the brush, and the sky is your canvas. As you wave your hand, drones paint glowing trails through the air like an artist sketching with light.
- **🎮 Air joystick**: Imagine your hand as a floating controller; each gesture becomes a button or lever that guides, directs, or reshapes a digital swarm.
- **🌈 Digital fireflies**: Just like fireflies respond to nature’s cues, these drones respond to your gestures — fluttering in formation, leaving behind trails that form glowing shapes, names, or artworks in the sky.

---

## 📊 Summary Table (for quick reference)

| ❓ Question | 📘 Answer Summary |
|------------|-------------------|
| **What is DronePaint?** | A gesture-based drone swarm painting system using DNN recognition for intuitive light-based art. 🎨🖐️🚁 |
| **How do hand gestures move the drones?** | Gestures are detected via webcam + MediaPipe + DNN and converted into drone flight paths via ROS. 🧠➡️🛫 |
| **What is the system architecture?** | Three-part system: gesture interface, path smoothing module, and drone control via ROS and potential fields. ⚙️📐 |
| **Why smooth the path before flying?** | To remove jitter and ensure safe, stable, and visually smooth drone movements. ✍️🔧🪄 |
| **Three metaphors for LightPaint** | 🖌️ "Sky brush", 🎮 "Air joystick", 🌈 "Digital fireflies" — each captures a creative way of imagining the system. |

> 📄 Based on: [DronePaint: Swarm Light Painting with DNN-based Gesture Recognition (SIGGRAPH '21)](https://doi.org/10.1145/3450550.3465349)
