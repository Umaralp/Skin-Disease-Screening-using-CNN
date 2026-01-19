## 📖 About the Project
**DermAI** is an AI-powered web application designed to act as a preliminary screening tool for skin lesions. Developed as part of the **1M1B AI for Sustainability Internship**, this project aligns with **UN Sustainable Development Goal 3 (Good Health and Well-being)** by leveraging deep learning to bridge the gap in healthcare accessibility.

##  Problem Statement
In many rural and underserved regions, access to specialized dermatologists is severely limited. Patients often face:
* High consultation costs.
* Long travel distances.
* Significant wait times.

This delay in diagnosis can lead to severe complications for treatable conditions like **Melanoma** or **Eczema**.

## 💡 Solution Overview
DermAI allows users to upload an image of a skin lesion and receive an instant analysis.
* **Input:** User uploads an image via a web interface.
* **Process:** The image is processed by a **Convolutional Neural Network (CNN)**.
* **Output:** The model classifies the lesion into one of 7 diagnostic categories with a confidence score.

**Note:** *This tool is for screening purposes only and does not replace professional medical advice.*

---

## 🛠 Tech Stack
* **Programming Language:** Python
* **Deep Learning Framework:** TensorFlow / Keras
* **Web Interface:** Gradio
* **Data Processing:** Pandas, NumPy, PIL

## 📂 Dataset
The model was trained on the **HAM10000 ("Human Against Machine")** dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions.
* **Source:** [Harvard Dataverse / Kaggle](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)
* **Classes:** Melanocytic nevi, Melanoma, Benign keratosis-like lesions, Basal cell carcinoma, Actinic keratoses, Vascular lesions, Dermatofibroma.
