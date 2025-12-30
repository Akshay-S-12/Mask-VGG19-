# 😷 Face Mask Detection Using Transfer Learning (VGG19)

This project implements a **Face Mask Detection system** using **Transfer Learning with VGG19**.  
The model classifies face images into **With Mask** and **Without Mask** categories using a pre-trained deep learning architecture.

The project demonstrates how **VGG19**, a deeper convolutional neural network, can be effectively reused for image classification tasks with limited data.

---

## 📌 Features
- 🧠 Uses **VGG19 pre-trained on ImageNet**
- 🔁 Transfer Learning with frozen convolutional layers
- 🖼️ Binary image classification: **With Mask / Without Mask**
- 📊 Training & validation accuracy visualization
- 💾 Trained model saved for reuse
- 🔍 Supports prediction on new images
- ⚡ Efficient training with limited dataset

---

## 🛠️ Technologies Used
- **Python**
- **TensorFlow / Keras**
- **VGG19 (Transfer Learning)**
- **OpenCV / scikit-image**
- **Matplotlib**
- **NumPy, Pandas**

---

## 📂 Project Structure
VGG19-Mask-Prediction/
│
├── Mask_VGG19.ipynb
├── Model_VGG19.h5
├── README.md
│
├── Maskdata/
│ ├── with_mask/
│ └── without_mask/
│
└── Maskdatatest/
├── with_mask/
└── without_mask/


## ⚙️ Model Architecture
- Base Model: **VGG19 (ImageNet weights)**
- Frozen convolutional layers for feature extraction
- Custom classifier:
  - Flatten layer
  - Dense layer with Softmax (2 classes)
- Optimizer: **Adam**
- Loss Function: **Categorical Crossentropy**
