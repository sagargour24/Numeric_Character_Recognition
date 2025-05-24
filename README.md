# 🔢 Numeric Character Recognition - Kaggle Competition (Top 5 Finish)

This project involves building a high-performance image classification model to recognize **handwritten numeric characters (0–9)**. The model was developed and fine-tuned as part of a Kaggle competition, where it achieved an impressive **5th place** ranking.

---

## 🏆 Competition Result

🥇 **Rank:** 5th Place  
📊 **Platform:** Kaggle  
🧾 **Proof:**  
<p align="center">
  <img src="images/kaggle_competition.png" alt="5th Place Proof" width="600">
</p>

---

## 📦 Dataset

- **Source:** Kaggle-provided dataset
- **Data Format:** Grayscale images of handwritten digits
- **Classes:** `0` through `9`
- **Shape:** `(28, 28)` pixel images

---

## 🧠 Model Architecture

The model leverages a Convolutional Neural Network (CNN) with the following components:

- Multiple `Conv2D + ReLU + MaxPooling` blocks
- `BatchNormalization` for training stability
- `Dropout` for regularization
- `Dense` output layer with Softmax activation

> Fine-tuned hyperparameters such as kernel size, learning rate, batch size, and optimizer helped achieve top performance.

---

## 🚀 How to Run

### 1. Install dependencies

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
