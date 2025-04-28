# Face Mask Detection Using CNN

This project is a deep learning-based **Face Mask Detection System** built using **TensorFlow** and **Keras**.  
The model classifies whether a person in an image is wearing a mask or not.

---

## Dataset
- Dataset used: **Custom Face Mask Dataset**
- Two categories:
  - With Mask (Label 0)
  - Without Mask (Label 1)

---

## Model Architecture
- Convolutional Neural Network (CNN)
- Layers:
  - Conv2D (32 filters) + MaxPooling2D
  - Conv2D (64 filters) + MaxPooling2D
  - Flatten
  - Dense (128 neurons) + Dropout (0.5)
  - Output Layer (2 neurons, Sigmoid activation)

Loss Function: `sparse_categorical_crossentropy`  
Optimizer: `adam`

---

## How to Run Locally

1. Clone the repo:

```bash
git clone https://github.com/joel-ginu-mathew/face-mask-detection.git
cd face-mask-detection
