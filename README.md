# Self-Driving Car using NVIDIA Model & Simulator

## 📌 Project Overview
This project implements a **self-driving car** using a **simulator** and an NVIDIA deep learning model. The model predicts steering angles based on input images from the simulator, enabling autonomous navigation.

## 🚀 Features
- Uses **Convolutional Neural Networks (CNNs)** for autonomous driving.
- Implements the **NVIDIA End-to-End Learning Model**.
- Trained on a driving simulator dataset.
- Real-time inference for steering control.

## 🛠️ Setup Instructions

### 1️⃣ Install Dependencies
Make sure you have Python (3.8 - 3.10) installed.
```sh
pip install --upgrade pip setuptools wheel
pip install tensorflow numpy matplotlib opencv-python pandas
```

### 2️⃣ Clone the Repository
```sh
git clone https://github.com/your-repo/self-driving-car
cd self-driving-car
```

### 3️⃣ Load the Pre-trained Model
Download the trained model and place it in the project directory:
```sh
model.h5  # Ensure the model file is in the same directory
```

### 4️⃣ Run the Self-Driving Car Simulation
```sh
python drive.py model.h5
```

## 📊 Model Architecture
The model follows NVIDIA’s architecture:
1. **Input Layer**: Preprocessed images from the simulator.
2. **Convolutional Layers**: Extracts features from road images.
3. **Fully Connected Layers**: Predicts the steering angle.

## 🎯 Results & Performance
- The model successfully navigates the test track in the simulator.
- Steering predictions are smooth with minimal drift.


