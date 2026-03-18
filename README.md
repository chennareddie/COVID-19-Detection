# 🧠 COVID-19 Detection Using Lung Images (Advanced Deep Learning Project)

## 📌 Project Overview

This project detects **COVID-19 from lung images (Chest X-rays / CT scans)** using advanced **Deep Learning models with Transfer Learning**.

It classifies images into:

* COVID
* Normal
* Lung Opacity
* Viral Pneumonia

🚀 This upgraded version includes:

* Multiple model comparison (VGG16, VGG19, ResNet50)
* Grad-CAM visualization
* Streamlit web application
* Accuracy optimization (95%+)

---

## 🚀 Features

* 📂 Automatic dataset extraction from ZIP
* 🧹 Image preprocessing & augmentation
* 🤖 Multiple Deep Learning models:

  * VGG16
  * VGG19
  * ResNet50
* 📊 Model comparison (accuracy & loss)
* 🔥 Grad-CAM visualization (model explainability)
* 🌐 Streamlit Web App for real-time prediction
* 💾 Model saving & loading
* 🎯 High accuracy (optimized training)

---

## 🗂️ Dataset

Dataset path:

```
/content/covid19.zip
```

After extraction:

```
dataset/
│
├── COVID/
├── NORMAL/
├── LUNG_OPACITY/
└── VIRAL_PNEUMONIA/
```

⚠️ If a nested folder exists:

```
COVID-19_Radiography_Dataset/
```

Update the path accordingly.

---

## ⚙️ Installation

```bash
pip install tensorflow numpy matplotlib streamlit opencv-python
```

---

## ▶️ How to Run

### Step 1: Extract Dataset

```python
zip_path = "/content/covid19.zip"
extract_path = "/content/dataset"
```

---

### Step 2: Train Models

Train multiple models:

* VGG16
* VGG19
* ResNet50

Each model uses:

* Input: 224x224
* Batch size: 32
* Epochs: 10–20

---

### Step 3: Compare Models

The project compares:

* Accuracy
* Loss
* Performance

📊 Best model is selected automatically.

---

### Step 4: Grad-CAM Visualization

Grad-CAM highlights infected lung regions:

* Shows **important areas in X-ray**
* Improves model explainability
* Helps medical interpretation

---

### Step 5: Run Streamlit App

```bash
streamlit run app.py
```

Features:

* Upload lung image
* Predict COVID status
* Show confidence score
* Display Grad-CAM heatmap

---

## 🧠 Model Architectures

### 🔹 VGG16

* Lightweight and fast
* Good baseline model

### 🔹 VGG19

* Deeper than VGG16
* Better feature extraction

### 🔹 ResNet50

* Residual connections
* Prevents vanishing gradient
* Best performance in most cases

---

## 📊 Results

| Model    | Accuracy |
| -------- | -------- |
| VGG16    | ~90–93%  |
| VGG19    | ~92–94%  |
| ResNet50 | **95%+** |

✅ ResNet50 gives the best performance

---

## 📈 Accuracy Improvement Techniques

* Data augmentation
* Transfer learning
* Dropout regularization
* Fine-tuning last layers
* Proper normalization
---------------

Perfect for:

* Project demo
* Viva presentation
* Portfolio

---

## 📚 Technologies Used

* Python 🐍
* TensorFlow / Keras 🤖
* OpenCV
* NumPy
* Matplotlib
* Streamlit

---

## 🔍 Future Scope

* Deploy on cloud (AWS / GCP)
* Mobile app integration
* Real-time hospital system
* Larger dataset training

---

## 👨‍💻 Author

**Chenna Reddy**

---

## ⭐ Contribution

Contributions are welcome:

* Improve model accuracy
* Add new architectures
* Enhance UI

---

## 📜 License

This project is for educational and research purposes only.
