# IoT-Project-Ligh-Controlling-Using-Hand-Guestures
This project explores **Hand Gesture Recognition (HGR)** technology to control lights via gestures. It integrates **machine learning**, **computer vision**, and **IoT (Internet of Things)** to create a natural interaction system. The project is structured as part of the **AI Vietnam All-in-One Course**.

## Objectives

- Develop a **Natural Interaction System** for controlling lights.
- Set up the project environment.
- Collect and prepare gesture data.
- Build and train a **Multi-Layer Perceptron (MLP)** model for gesture recognition.
- Evaluate model performance.
- Deploy real-time gesture recognition for simulation and real-world applications.

---

## Project Overview

### What is Hand Gesture Recognition (HGR)?
Hand Gesture Recognition identifies and interprets hand and finger movements to enable intuitive interaction between humans and systems like computers or robots. Applications include:

- **Healthcare**
- **Education**
- **Entertainment**
- **Human-Computer Interaction (HCI)**
- **Human-Robot Interaction (HRI)**

### Key Components:
1. **Data Acquisition**: Use cameras or sensors (e.g., Mediapipe) to capture gesture data.
2. **Feature Extraction**: Analyze images to extract key features like hand positions and movements.
3. **Classification**: Use machine learning or deep learning models (e.g., MLP) to classify gestures into predefined categories.

### Types of Gestures:
- **Static Gestures**: Fixed hand positions (e.g., pointing, specific shapes).
- **Dynamic Gestures**: Movements over time (e.g., waving, drawing patterns).

---

## Implementation Steps

### Step 0: Generate Data
- Define gesture classes using tools like `generate_landmark_data.py` and `gesture_classes.csv`.
- Collect gesture data using **Mediapipe** for palm detection and hand landmark detection.

### Step 1: Hand Gesture Classification
- Use a **Multi-Layer Perceptron (MLP)** model:
  - **Input Layer**: Extracted features from gestures.
  - **Hidden Layers**: Process inputs using weighted connections and activation functions.
  - **Output Layer**: Classify gestures into categories.
- Train and evaluate the model.

### Step 2: Light Control (Simulation and Reality)
- Simulate the lighting system using the best MLP model.
- Deploy the system on real devices for live testing and control.

---

## Tools and Technologies

- **Mediapipe**: For hand landmark detection.
- **Python**: Core programming language for implementation.
- **MLP Model**: Neural network for gesture classification.

---

## Key Features

- **Real-Time Gesture Recognition**: Recognize and respond to gestures instantly.
- **Simulation Mode**: Test the system without physical hardware.
- **IoT Integration**: Control real-world lights with recognized gestures.