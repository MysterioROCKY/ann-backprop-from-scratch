# ANN with Backpropagation from Scratch

This repository provides a complete implementation of an Artificial Neural Network (ANN) using the backpropagation algorithm from scratch in Python, without any ML libraries like TensorFlow or PyTorch. It covers two tasks: fitting a sine curve and predicting power output using the Combined Cycle Power Plant (CCPP) dataset.

---

## 📁 Folder Structure

---

## 🧠 Task 1: Fitting y = sin(x)

- File: `q1_fitting_sinx_curve.py`
- Uses a feedforward ANN to approximate the sine function.
- NumPy-based implementation with no ML libraries.
- Trained using gradient descent and MSE loss.

---

## ⚡ Task 2: Predicting Power Output from CCPP Dataset

- File: `q2_ccpp_dataset.py`
- Dataset files are located inside:  
  `combined+cycle+power+plant/CCPP/`
- Predicts power output (PE) based on:
  - Ambient Temperature (AT)
  - Exhaust Vacuum (V)
  - Ambient Pressure (AP)
  - Relative Humidity (RH)
- Uses `Folds5x2_pp.xlsx` and `Folds5x2_pp.ods` as inputs.

---

## 📄 Assignment PDF

- `Assignment 1 - ANN with Backprop.pdf` contains:
  - Task descriptions
  - Expected outputs
  - Constraints and guidance

---

## 🛠️ How to Run

1. **Clone the repo**:
   ```bash
   git clone https://github.com/MysterioROCKY/ann-backprop-from-scratch.git
   cd ann-backprop-from-scratch
