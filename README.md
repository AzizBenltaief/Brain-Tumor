# 🧠 Brain Tumor Classification with CNN (PyTorch)

This project builds a **Convolutional Neural Network (CNN)** using **PyTorch** to classify brain MRI images into one of four categories. It uses custom training and testing datasets and is optimized for GPU acceleration if available.

## 🔍 Overview

This project follows a typical image classification pipeline:

1. **Image Preprocessing**:
   - Resize to 128×128
   - Normalize to [-1, 1]
   - Convert to PyTorch tensors

2. **Model Architecture**:
   - 3 convolutional layers with ReLU and MaxPooling
   - Flatten layer followed by fully connected layers
   - Dropout for regularization
   - Output layer with 4 neurons (for 4 classes)

3. **Training**:
   - Optimizer: Adam (`1e-4`)
   - Loss Function: CrossEntropyLoss
   - Epochs: 25
   - Batch Size: 32

4. **Evaluation**:
   - Reports overall test loss and accuracy

---

## 🧠 Technologies Used

- **Python**
- **PyTorch**
- **Torchvision**
- **CUDA (GPU support if available)**



