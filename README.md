# 🤖 Machine Learning & Data Science Projects Portfolio

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-1.0-yellow)
![Status](https://img.shields.io/badge/Status-Active-green)

This repository is a collection of my **Machine Learning** and **Deep Learning** projects, showcasing various algorithms applied to real-world datasets. Each project demonstrates a specific problem-solving approach, from **Image Segmentation** to **Disease Classification**.

## 📂 Project Catalog (Proje Kataloğu)

| 📌 Project Name | 📊 Data Type | 🧠 Algorithm / Model | 📈 Performance | 📝 Description |
| :--- | :--- | :--- | :---: | :--- |
| **[Concrete Crack Detection](concrete-cracks.ipynb)** | 🖼️ Image | **MobileNetV2 (Transfer Learning)** | **~99.04%** (Val) | Detected structural cracks in concrete surfaces for maintenance safety. |
| **[Magnetic Tile Defect](tile-defect.ipynb)** | 🖼️ Image | **Custom CNN** | **~91.28%** (Val) | Classified 5 different types of manufacturing defects (Blowhole, Break, Crack, etc.) in magnetic tiles. |
| **[Ceramic Crack Segmentation](crackforest.ipynb)** | 🖼️ Image | **U-Net (MobileNetV2 Backbone)** | **~96.37%** (Train) | Performed semantic segmentation to identify the exact pixel location of cracks on ceramic surfaces. |
| **[Breast Cancer Classification](breast_cancer_dataset.ipynb)** | 🔢 Tabular | **Logistic Regression** | **~97.37%** (Test) | Classified tumors as Malignant (M) or Benign (B) using the Breast Cancer Wisconsin dataset. |
| **[Diabetes Prediction](diabets_dataset_training_with_KNN,_Logistic_Regression_and_Decision_Tree_models.ipynb)** | 🔢 Tabular | **KNN & Decision Tree** | **~79.22%** (Test) | Predicted diabetes onset based on health metrics. Decision Tree provided the best balance between accuracy and interpretability. |

---

## 🔍 Project Details (Proje Detayları)

### 1. 🧱 Concrete Crack Detection (Beton Çatlak Tespiti)
* **Goal:** To automate the detection of cracks in concrete structures.
* **Dataset:** Concrete Crack Images (Positive/Negative).
* **Model:** **MobileNetV2** (Pre-trained) with a custom classification head.
* **Key Insight:** Transfer learning significantly reduced training time while achieving near-perfect accuracy on the validation set.

### 2. 🧲 Magnetic Tile Defect Classification (Manyetik Fayans Hata Tespiti)
* **Goal:** To classify manufacturing defects in magnetic tiles into 5 categories (Blowhole, Break, Crack, Fray, Free).
* **Dataset:** Magnetic Tile Defect Dataset.
* **Model:** **Custom CNN Architecture** (3 Conv2D layers + MaxPooling + Dense).
* **Result:** The model successfully generalized to unseen data with **~91% validation accuracy**, proving effective for industrial quality control.

### 3. 🏺 Ceramic Crack Segmentation (Seramik Çatlak Segmentasyonu)
* **Goal:** To pinpoint the exact location of cracks on ceramic tiles (Pixel-level Classification).
* **Dataset:** Ceramic Cracks Dataset.
* **Model:** **U-Net** architecture using **MobileNetV2** as the encoder (backbone).
* **Result:** Achieved **96.37% training accuracy**, effectively separating fine crack lines from the background texture.

### 4. 🎗️ Breast Cancer Classification (Meme Kanseri Teşhisi)
* **Goal:** To assist medical diagnosis by classifying breast mass features.
* **Dataset:** Breast Cancer Wisconsin (Diagnostic).
* **Model:** **Logistic Regression**.
* **Result:** Achieved **97.37% accuracy**. The model distinguished between malignant and benign tumors with high precision.

### 5. 🍬 Diabetes Prediction (Diyabet Tahmini)
* **Goal:** To predict diabetes probability based on diagnostic measures (Glucose, BMI, Age, etc.).
* **Dataset:** Pima Indians Diabetes Database.
* **Models Compared:** Logistic Regression (~72%), KNN (~75%), **Decision Tree (~79%)**.
* **Result:** Decision Tree outperformed others, capturing non-linear relationships in patient data.

---

## 🛠️ Tools & Libraries Used
* **Languages:** Python
* **Deep Learning:** TensorFlow, Keras
* **Machine Learning:** Scikit-Learn
* **Data Processing:** Pandas, NumPy, PIL
* **Visualization:** Matplotlib, Seaborn

## 📫 Contact
If you have any questions or suggestions about these projects, feel free to reach out!

[LinkedIn Profile](https://www.linkedin.com/in/furkan-izmir-017249331/) | [Email](f.izmir03@gmail.com)
