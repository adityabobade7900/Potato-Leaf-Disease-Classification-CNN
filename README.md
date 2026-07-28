# 🥔 Potato Leaf Disease Classification using CNN

A deep learning project that classifies potato leaf diseases using a Convolutional Neural Network (CNN). The model identifies three classes of potato leaf images with high accuracy using TensorFlow and Keras.

## 📌 Project Overview

Potato diseases can significantly reduce crop yield if not detected early. This project uses a CNN model to automatically classify potato leaf images into the following categories:

- 🟤 Potato Early Blight
- ⚫ Potato Late Blight
- 🟢 Healthy Potato Leaf

The model was trained on a labeled image dataset and achieved excellent classification performance.

---

## 🚀 Features

- CNN-based image classification
- Three-class disease detection
- Image preprocessing and normalization
- Model evaluation using Classification Report and Confusion Matrix
- High prediction accuracy
- Built using TensorFlow and Keras

---

## 📊 Model Performance

| Metric | Value |
|--------|-------|
| Test Accuracy | **98.27%** |
| Precision | **97% - 100%** |
| Recall | **97% - 99%** |
| F1-Score | **97% - 100%** |

### Classification Report

| Class | Precision | Recall | F1-Score |
|------|:---------:|:------:|:--------:|
| Potato Early Blight | 1.00 | 0.99 | 1.00 |
| Potato Late Blight | 0.98 | 0.98 | 0.98 |
| Healthy Potato Leaf | 0.97 | 0.97 | 0.97 |

---

## 🧠 CNN Architecture

```
Input Image (256 × 256 × 3)
        │
Conv2D (32 Filters)
        │
MaxPooling2D
        │
Dropout
        │
Conv2D (64 Filters)
        │
MaxPooling2D
        │
Dropout
        │
Conv2D (128 Filters)
        │
MaxPooling2D
        │
Dropout
        │
Conv2D (256 Filters)
        │
MaxPooling2D
        │
Flatten
        │
Dense (128)
        │
Dropout
        │
Dense (64)
        │
Dense (32)
        │
Dense (16)
        │
Output Layer (Softmax)
```

---

## 📂 Dataset Classes

```
Potato___Early_blight
Potato___Late_blight
Potato___healthy
```

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
Potato-Leaf-Disease-Classification-CNN/
│
├── Dataset/
├── Potato_Disease_Prediction.ipynb
├── Potato_Disease_Prediction.keras
├── requirements.txt
├── README.md
└── Images/
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/adityabobade7900/Potato-Leaf-Disease-Classification-CNN.git
```

Move to the project directory:

```bash
cd Potato-Leaf-Disease-Classification-CNN
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Potato_Disease_Prediction.ipynb
```

Train the model or use the saved model for prediction.

---

## 📈 Future Improvements

- Deploy using Streamlit
- Mobile application integration
- Real-time disease detection
- Support additional plant diseases
- Model optimization for faster inference

---

## 👨‍💻 Author

**Aditya Bobade**

- GitHub: https://github.com/adityabobade7900
- LinkedIn: www.linkedin.com/in/aditya-bobade7900

---

## ⭐ If you found this project useful, don't forget to star the repository!