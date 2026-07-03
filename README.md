# 🌿 Crop Disease Prediction System

An AI-powered desktop application for multi-crop disease prediction using **VGG16 Transfer Learning**, **PyTorch**, and **Grad-CAM Explainability** with an intuitive **PyQt5 graphical interface**.

---

## 📖 Overview

The Crop Disease Prediction System is a desktop application designed to assist in the early detection of plant diseases using deep learning. Users can upload a leaf image, select the corresponding crop, and receive disease predictions with confidence scores. The application also provides **Grad-CAM visualization**, allowing users to understand which regions of the leaf influenced the model's prediction.

---

## ✨ Features

- Multi-crop disease prediction
- User-friendly PyQt5 desktop interface
- Upload leaf images for prediction
- Top-2 disease predictions with confidence scores
- Grad-CAM explainability
- Automatic CPU/GPU detection
- Splash screen and responsive UI
- Seven independently trained VGG16 models

---

## 🌱 Supported Crops

- Corn
- Cotton
- Potato
- Rice
- Sugarcane
- Tea
- Wheat

---

## 🧠 Model Architecture

- Transfer Learning using VGG16
- PyTorch
- Image Size: 224 × 224
- Data Augmentation
- Dropout Regularization
- Grad-CAM Explainability

---

## 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Deep Learning | PyTorch, Torchvision |
| GUI | PyQt5 |
| Computer Vision | OpenCV |
| Image Processing | Pillow |
| Data Analysis | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Evaluation | Scikit-learn |

---

## 📂 Project Structure

```text
Crop-Disease-Prediction-System
│
├── ui
├── inference
├── explainability
├── model_training
├── results
├── screenshots
├── docs
├── demo
├── requirements.txt
├── dataset_links.md
└── README.md
```

---

## 🚀 Installation

Clone the repository.

```bash
git clone https://github.com/YOUR_USERNAME/Crop-Disease-Prediction-System.git
```

Navigate to the project directory.

```bash
cd Crop-Disease-Prediction-System
```

Install the required packages.

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python ui/app.py
```

---

## 📊 Datasets

The datasets are **not included** in this repository due to their size.

Dataset download links are available in:

```
dataset_links.md
```

---

## 🧩 Model Files

Pre-trained model weights (`.pth`) are **not included** in this repository.

Place the downloaded model files inside:

```text
saved_models/
```

before running the application.

---

## 📸 Screenshots

Screenshots will be added here.

- Home Screen
- Upload Image
- Prediction
- Grad-CAM Visualization
- Splash Screen

---

## 🎥 Demo

A demonstration video of the application will be added here.

---

## 📈 Future Improvements

- Additional crop support
- Mobile application
- Cloud deployment
- Real-time camera prediction
- Web-based interface
- Model optimization for faster inference

---

## 👨‍💻 Author

**Abhay**

B.Tech Computer Science Engineering

---

## 📄 License

This project is licensed under the MIT License.
