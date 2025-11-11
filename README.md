# 🧠 MNIST Handwritten Digit Classifier

A Deep Learning project that classifies handwritten digits (0–9) using **TensorFlow** and **Keras** on the classic **MNIST dataset**.  
The project demonstrates image preprocessing, neural network training, and prediction visualization — a foundational step toward mastering computer vision.

---

## 📁 Project Overview

This project builds, trains, and evaluates a neural network model to recognize handwritten digits from grayscale 28x28 pixel images.

**Goal:** Achieve accurate multi-class classification of digits using a feedforward or CNN-based neural network.

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Libraries:** TensorFlow, NumPy, Matplotlib  
- **Dataset:** MNIST (via `tensorflow.keras.datasets`)

---

## 🧩 Workflow

1. **Import and Load Data**
   - Loaded MNIST dataset from TensorFlow.
   - Split into training and test sets.

2. **Preprocessing**
   - Normalized pixel values.
   - Reshaped data for model input.

3. **Model Architecture**
   - Sequential model using dense or convolutional layers.
   - ReLU activation, softmax output.

4. **Model Training**
   - Compiled with categorical crossentropy and Adam optimizer.
   - Trained using `.fit()` on training data.

5. **Visualization**
   - Displayed sample digits.
   - Visualized training accuracy and loss curves.

---

## 📊 Results

- Successfully trained on 60,000 training images and tested on 10,000 images.
- Achieved strong recognition accuracy on unseen handwritten digits.
- Visualized predictions and digit samples for verification.

*(Note: Accuracy and confusion matrix evaluation can be extended for deeper analysis.)*

---

## 🧠 Key Learnings

- Image data normalization and reshaping.
- Building and training deep neural networks with TensorFlow/Keras.
- Importance of model evaluation and visualization.
- Foundation for more advanced CNN architectures (e.g., LeNet, VGG).

---

## 🚀 Future Improvements

- Add **accuracy, confusion matrix, and classification report** for better evaluation.
- Implement **Convolutional Neural Network (CNN)** for higher accuracy.
- Save and deploy model with **Streamlit or Flask**.
- Integrate **hyperparameter tuning** with KerasTuner.

---

## 📌 Author

**Vasu Agrawal**  
Machine Learning & AI Engineering Enthusiast  
[LinkedIn](https://www.linkedin.com/in/vasu-agrawal20/) | [GitHub](https://github.com/vasuag09)
