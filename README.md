# 🥔 Potato Disease Classification using CNN & Deep Learning

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)](https://python.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?style=for-the-badge&logo=tensorflow)](https://www.tensorflow.org)
![CNN](https://img.shields.io/badge/CNN-Image%20Classification-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

### 🌱 AI-Powered Potato Leaf Disease Detection System

A Deep Learning project that uses Convolutional Neural Networks (CNNs) to automatically identify potato plant diseases from leaf images.

</div>

---

# 📌 Project Overview

Potato crops are vulnerable to various diseases that can significantly reduce agricultural productivity. Early disease detection is essential for preventing crop loss.

This project leverages **Deep Learning and Computer Vision** techniques to classify potato leaf images into different disease categories with high accuracy.

The model is trained using a **Convolutional Neural Network (CNN)** that learns important visual patterns from potato leaf images and predicts the disease class.

---

# 🎯 Objectives

- Detect potato leaf diseases automatically.
- Reduce manual inspection efforts.
- Improve early disease diagnosis.
- Apply Deep Learning concepts in agriculture.
- Build an intelligent image classification system.

---

# 🦠 Disease Categories

The model classifies potato leaves into:

| Class | Description |
|---------|-------------|
| Healthy | Healthy Potato Leaf |
| Early Blight | Fungal Disease |
| Late Blight | Severe Potato Disease |

---

# 🧠 Deep Learning Concepts Used

### Convolutional Neural Networks (CNN)

The project uses CNN architecture consisting of:

✅ Convolution Layers

✅ ReLU Activation Function

✅ Max Pooling Layers

✅ Dropout Layers

✅ Dense (Fully Connected) Layers

✅ Softmax Classification Layer

---

# 🏗️ Model Architecture

```text
Input Image
      ↓
Convolution Layer
      ↓
ReLU Activation
      ↓
Max Pooling
      ↓
Convolution Layer
      ↓
Max Pooling
      ↓
Flatten
      ↓
Dense Layer
      ↓
Dropout
      ↓
Output Layer (3 Classes)
```

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| TensorFlow | Deep Learning Framework |
| Keras | CNN Model Building |
| NumPy | Numerical Computation |
| Pandas | Data Processing |
| Matplotlib | Visualization |
| OpenCV | Image Processing |
| Jupyter Notebook | Development Environment |

---

# 📂 Dataset

The dataset contains potato leaf images belonging to three classes:

- Healthy
- Early Blight
- Late Blight

Dataset Source:

🌿 PlantVillage Dataset

---

# 📁 Project Structure

```text
Potato-Disease-Classification/
│
├── dataset/
│   ├── Healthy/
│   ├── Early_Blight/
│   └── Late_Blight/
│
├── models/
│   └── potato_cnn_model.h5
│
├── notebooks/
│   └── training.ipynb
│
├── images/
│   └── sample_predictions.png
│
├── train.py
├── predict.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Potato-Disease-Classification.git
```

Move into project directory:

```bash
cd Potato-Disease-Classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 🚀 Training the Model

```bash
python train.py
```

The CNN model will:

- Load dataset
- Perform preprocessing
- Train on potato leaf images
- Save trained model

---

# 🔍 Making Predictions

```bash
python predict.py
```

Upload a potato leaf image and the model will predict its disease category.

---

# 📊 Results

| Metric | Value |
|----------|---------|
| Training Accuracy | XX% |
| Validation Accuracy | XX% |
| Test Accuracy | XX% |



---

# 📈 Future Improvements

- Implement Transfer Learning (ResNet, EfficientNet)
- Deploy using Streamlit
- Create Mobile Application
- Add More Crop Diseases
- Real-Time Disease Detection

---

# 💡 Applications

- Smart Farming
- Precision Agriculture
- Crop Monitoring
- Disease Diagnosis
- Agricultural Research

---

# 🤝 Contribution

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make changes
4. Submit a Pull Request


---

# ⭐ If you found this project useful, don't forget to star the repository!
