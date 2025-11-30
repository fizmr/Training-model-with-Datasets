# 🤖 Machine Learning & Data Science Projects Portfolio

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-1.0-yellow)
![Status](https://img.shields.io/badge/Status-Active-green)

This repository is a collection of my **Machine Learning** and **Deep Learning** projects, showcasing various algorithms applied to real-world datasets. Each project demonstrates a specific problem-solving approach, from **Image Segmentation** to **Disease Classification**.

## 📂 Project Catalog (Proje Kataloğu)

| 📌 Project Name | 📊 Data Type | 🧠 Algorithm / Model | 📈 Performance (Accuracy) | 📝 Description |
| :--- | :--- | :--- | :---: | :--- |
| **[Concrete Crack Detection](Concrete_Crack_Detection_CNN.ipynb)** | 🖼️ Image | **MobileNetV2 (Transfer Learning)** | **~99.04%** | Detected structural cracks in concrete surfaces using a pre-trained MobileNetV2 model. Achieved high accuracy on the validation set. |
| **[Breast Cancer Classification](Breast_Cancer_Classification.ipynb)** | 🔢 Tabular | **Logistic Regression** | **~97.37%** | Classified tumors as Malignant (M) or Benign (B) using the Breast Cancer Wisconsin dataset. High precision and recall were observed. |
| **[Diabetes Prediction](Diabetes_Prediction_KNN.ipynb)** | 🔢 Tabular | **KNN & Decision Tree** | **~79.22%** | Predicted diabetes onset based on health metrics like Glucose, BMI, and Age. Decision Tree outperformed Logistic Regression and KNN. |
| **[Ceramic Crack Segmentation](Crack_Forest.ipynb)** | 🖼️ Image | **U-Net (MobileNetV2 Backbone)** | **~96.37%** | Performed semantic segmentation to identify cracks on ceramic surfaces. Used a U-Net architecture with a MobileNetV2 encoder. |

---

## 🔍 Project Details (Proje Detayları)

### 1. 🧱 Concrete Crack Detection (Beton Çatlak Tespiti)
* **Goal:** To automate the detection of cracks in concrete structures for maintenance safety.
* **Dataset:** Concrete Crack Images for Classification (40,000 images).
* **Model:** **MobileNetV2** (Pre-trained on ImageNet) with custom classification head.
* **Result:** The model achieved **99.04% validation accuracy**, proving highly effective for structural health monitoring.

### 2. 🎗️ Breast Cancer Classification (Meme Kanseri Teşhisi)
* **Goal:** To assist medical diagnosis by classifying breast mass features.
* **Dataset:** Breast Cancer Wisconsin (Diagnostic) Data Set.
* **Model:** **Logistic Regression**.
* **Result:** Achieved **97.37% accuracy**. The model successfully distinguished between malignant and benign tumors with very few false negatives.

### 3. 🍬 Diabetes Prediction (Diyabet Tahmini)
* **Goal:** To predict whether a patient has diabetes based on diagnostic measures.
* **Dataset:** Pima Indians Diabetes Database.
* **Models Compared:**
    * Logistic Regression: ~72%
    * K-Nearest Neighbors (KNN): ~75%
    * **Decision Tree (Winner): ~79.22%**
* **Result:** Decision Tree provided the best balance between accuracy and interpretability for this tabular dataset.

### 4. 🏺 Ceramic Crack Segmentation (Seramik Çatlak Segmentasyonu)
* **Goal:** To identify the exact pixel location of cracks on ceramic tiles (Semantic Segmentation).
* **Dataset:** Ceramic Cracks Dataset.
* **Model:** **U-Net Architecture** with MobileNetV2 as the encoder backbone.
* **Result:** The model reached **96.37% training accuracy**, effectively segmenting fine crack lines from the background.

---

## 🛠️ Tools & Libraries Used
* **Languages:** Python
* **Deep Learning:** TensorFlow, Keras
* **Machine Learning:** Scikit-Learn
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

## 📫 Contact
If you have any questions or suggestions about these projects, feel free to reach out!

[LinkedIn Profile](https://www.linkedin.com/in/furkan-izmir-017249331/) | [Email](f.izmir03@gmail.com)
