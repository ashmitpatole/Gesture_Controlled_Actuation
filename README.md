# Gesture Controlled Actuation System using Computer Vision

This project implements a real-time hand gesture recognition system to control hardware devices such as LEDs and servo motors. The system uses computer vision to detect hand gestures through a webcam and sends commands to an Arduino for actuation.

## Technologies Used
- Python
- OpenCV
- MediaPipe
- Arduino
- Servo Motor
- Serial Communication

## Project Overview
The system detects hand gestures using MediaPipe’s hand tracking module and processes the landmarks with OpenCV. Detected gestures are mapped to commands which are transmitted via serial communication to an Arduino microcontroller.

The Arduino then actuates LEDs and servo motors according to the received commands.

## Features
- Real-time hand gesture recognition
- Contactless control of hardware devices
- Integration of computer vision with embedded systems
- Gesture-to-command mapping system

## System Architecture
Camera → Python (OpenCV + MediaPipe) → Serial Communication → Arduino → Actuators (LED / Servo)

## Demonstration
(Add images or a short demo video here)

## Future Improvements
- Add more gesture commands
- Implement gesture classification using machine learning
- Integrate with ROS2 for robotic control systems
