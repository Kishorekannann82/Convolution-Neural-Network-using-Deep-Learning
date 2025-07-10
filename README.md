# 🧠 CIFAR-10 Image Classification with CNN (TensorFlow)

This project demonstrates how to build a **Convolutional Neural Network (CNN)** using **TensorFlow** and **Keras** to classify images from the **CIFAR-10 dataset**.

---

## 📦 Dataset
**CIFAR-10** is a widely-used dataset consisting of:
- **60,000 color images** (32x32 pixels)
- **10 classes**:
  - Airplane
  - Automobile
  - Bird
  - Cat
  - Deer
  - Dog
  - Frog
  - Horse
  - Ship
  - Truck

---

## 🔧 Technologies & Libraries
- Python
- TensorFlow / Keras
- NumPy

---

## 📋 Project Structure
├── cifar10_cnn.py # Python script containing the model
├── README.md # Project documentation (this file)




---

## 🚀 Model Architecture
- **Conv2D (32 filters, 3x3 kernel, ReLU)**
- **MaxPooling2D (2x2 pool size)**
- **Conv2D (64 filters, 3x3 kernel, ReLU)**
- **MaxPooling2D (2x2 pool size)**
- **Conv2D (64 filters, 3x3 kernel, ReLU)**
- **Flatten**
- **Dense (64 neurons, ReLU)**
- **Dense (10 neurons, output layer)**

---

## 🏃 Steps:
1. **Load Dataset:**
   - CIFAR-10 images and labels.
2. **Preprocessing:**
   - Normalize pixel values to range [0,1].
3. **Model Building:**
   - Sequential CNN model.
4. **Model Compilation:**
   - Optimizer: Adam
   - Loss: Sparse Categorical Crossentropy (multi-class classification)
   - Metric: Accuracy
5. **Training:**
   - Train the model on the dataset for 10 epochs.
6. **Evaluation:**
   - Test the model’s accuracy on the test set.

---

## ✅ Commands to Run
```bash
python cifar10_cnn.py


📚 Learning Goals:
Understand CNN basics.

Learn TensorFlow/Keras model building and training.

Practice image classification tasks.
