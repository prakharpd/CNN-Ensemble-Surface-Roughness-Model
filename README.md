# Surface Roughness Prediction using CNN + ML Ensemble

## 🔍 Project Summary (GitHub + ATS Optimized)

**Domain:** Machine Learning, Deep Learning, Computer Vision, Manufacturing Analytics
**Role Alignment:** ML Engineer | AI Engineer | Data Scientist | Computer Vision Engineer

This project implements an **end-to-end machine learning pipeline** for predicting **surface roughness (Ra)** of **Inconel material** using a **hybrid CNN + machine learning ensemble approach**. The system combines **image-based feature extraction** from microscopic surface images with **numerical machining parameters**, followed by **ensemble regression** for accurate prediction.

The focus of this project is on **robust ML system design**, effective **feature fusion**, and **reproducibility**, rather than black-box end-to-end learning.

---

## 🧠 Key Skills & Technologies (ATS Keywords)

* Machine Learning & Deep Learning
* Convolutional Neural Networks (CNN)
* Computer Vision (OpenCV)
* Feature Engineering & Feature Fusion
* Ensemble Learning
* Regression Modeling
* Error Analysis & Data Cleaning
* Python, TensorFlow, Keras
* Scikit-learn
* NumPy, Pandas
* Manufacturing Analytics / Industry 4.0

---

## 📌 Problem Statement

Surface roughness is a critical quality metric in machining processes. Traditional analytical and empirical models struggle to generalize under limited experimental data and complex surface textures.

This project addresses the problem by:

* Extracting **deep visual features** from surface images using a custom CNN
* Integrating **machining parameters** with image features
* Applying **ensemble regression models** for improved generalization

---

## 📂 Data Description

* **Material:** Inconel
* **Data Type:**

  * Microscopic surface images (PNG format)
  * Corresponding machining parameters (numerical)
* **Image Naming Convention:** `SampleX_ImageY.png`
* Each image is associated with a unique machining condition and measured surface roughness value

> Note: Dataset is experimental and intended for academic/research use.

---

## 🧩 System Architecture

### 1. Image Preprocessing

* Image resizing and normalization
* Data augmentation to improve generalization

### 2. CNN-Based Feature Extraction

* Custom CNN architecture trained from scratch
* CNN used strictly as a **feature extractor**
* High-level texture and morphology features extracted from surface images

### 3. Feature Fusion

* CNN-extracted features concatenated with machining parameters
* Numerical features scaled before fusion

### 4. Ensemble Regression

* Machine learning regressors trained on fused feature space
* Supports ensemble strategies such as:

  * Gradient Boosting
  * Random Forest
  * XGBoost
  * Stacking-based regression

---

## 📁 Repository Structure

```
├── CNN_Ensemble_V1.ipynb
├── Images/
│   ├── SampleX_ImageY.png
│   └── ...
├── best_feature_extractor.keras
├── ensemble_model.pkl
├── parameter_scaler.pkl
└── README.md
```

---

## ⚙️ Tech Stack

* **Programming Language:** Python
* **Deep Learning:** TensorFlow, Keras
* **Computer Vision:** OpenCV
* **Machine Learning:** Scikit-learn
* **Data Handling:** NumPy, Pandas
* **Visualization:** Matplotlib

---

## ▶️ How to Run

1. Clone the repository
2. Install required dependencies
3. Ensure image directory structure is preserved
4. Open and run `CNN_Ensemble_V1.ipynb`
5. The best-performing models are saved automatically

---

## 🔁 Reproducibility & ML Best Practices

* Controlled data splits
* Model checkpointing
* Feature scaling and versioning

Designed to ensure **consistent and repeatable results**, aligning with real-world ML engineering standards.

---

## 🧪 Applications

* Smart Manufacturing Systems
* Automated Quality Control
* Surface Integrity Prediction
* Industry 4.0–enabled analytics

---

## 📈 Key Contributions

* Designed a **custom CNN feature extractor** for surface texture analysis
* Implemented **feature-level fusion** of vision and numerical data
* Applied **ensemble learning** for improved robustness on small datasets
* Built a **modular and extensible ML pipeline** suitable for research and deployment

---

## 👨‍💻 Author

**Prakhar Dwivedi**
B.Tech – NIT Andhra Pradesh
Aspiring ML / AI Engineer

---

## 📄 License

This project is intended for academic and research purposes. Commercial usage requires prior permission.

* This model was further used as Pre-Trained Mode for Real Time Surface Roughness Predicition.
* Images can not be uploaded into Github. As it exceeds storage limit.
