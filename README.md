# AI-Calculator
# 🧮 AI-Powered Virtual Calculator

An AI-based Virtual Calculator that allows users to perform mathematical operations by drawing expressions in the air using hand gestures. Built using **OpenCV**, this project integrates **computer vision** and **gesture recognition** to provide a contactless and intuitive interface for writing and evaluating mathematical expressions.

## ✨ Features

- ✅ Real-time finger tracking using a webcam.
- ✍️ Draw mathematical expressions on a virtual canvas.
- 🖐️ Intelligent gesture control to:
  - Start/stop drawing based on finger position.
  - Erase gestures for clean input.
- 📐 Supports basic arithmetic like `+`, `-`, `*`, `/`, and digits.
- 🧠 AI techniques to improve gesture detection and expression accuracy.

## 🚀 Tech Stack

- **Language:** Python
- **Libraries:** 
  - `OpenCV` – for real-time video processing and gesture tracking
  - `NumPy` – for array operations
  - `Math` – for evaluation logic
- **Tools:**
  - Webcam (Laptop or external)
  - Hand detection using contours and landmarks

## 🖼️ How It Works

1. The webcam captures your hand movements.
2. When a specific gesture is detected (like index finger up), drawing begins.
3. Movements are traced onto a digital canvas.
4. When gesture stops or changes, the input is processed.
5. The expression is parsed and evaluated, and the result is displayed.


## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/virtual-calculator.git
   cd virtual-calculator

2. **Install Dependecies**
  ```bash
pip install opencv-python numpy

3. **Run the application**
 ```bash
python virtual_calculator.py


