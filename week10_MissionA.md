### 1. What is DronePaint?
DronePaint is a human-swarm interaction system that enables users to control a drone swarm by drawing trajectories with hand gestures. Utilizing deep neural network-based gesture recognition, it allows real-time, device-free control of drone formations for applications like light painting and interactive drone shows
***
### 2. How do hand gestures move the drones?
Users perform hand gestures in front of a camera, which captures and processes the movements using the MediaPipe framework. The system then translates these gestures into trajectories that guide the drone swarm's flight path.
***
### 3. What is the system architecture?
The DronePaint system comprises three main modules:​

 1.Human-Swarm Interface: Captures and interprets hand gestures using a camera and gesture recognition software.​

 2.Trajectory Processing Module: Refines and prepares the drawn trajectories for drone execution.​

 3.Drone Control System: Directs the drone swarm based on the processed trajectories.​

 4.Hardware components include a Vicon Tracking system, Crazyflie 2.0 drones, and a Unity environment for visual feedback.
***
### 4. Why smooth my hand’s path before flying?
Smoothing the hand's path ensures that the generated trajectory is continuous and free from abrupt movements, which is crucial for precise drone control. This preprocessing step enhances the accuracy of the drone's flight path, reducing errors and improving the overall performance of the system. 
***
### 5. Three simple metaphors for LightPaint?
Digital Calligraphy: Drawing with light in the air, similar to writing with a glowing pen.​

Skywriting: Creating messages or images in the sky using light trails.​

Firefly Dance: A swarm of drones moving in harmony, leaving luminous patterns like a group of fireflies.
***

