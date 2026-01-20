# 🎗️ Breast Cancer Prediction Web App 🧬

A machine learning–based **web application** that predicts whether a breast tumor is **Benign or Malignant** using clinical features.  
The project integrates a trained ML classification model with an interactive **Gradio web interface**, enabling real-time predictions.

---

## 🌐 Web Application
This project includes a **Gradio-powered website** where users can input medical parameters and instantly receive prediction results.

https://f41bfb608a60d958a3.gradio.live/

---

## 📊 Dataset
The model is trained on the **Breast Cancer Wisconsin Dataset**, which contains features derived from digitized images of fine needle aspirate (FNA) of breast masses.

Key features include:
- Radius  
- Texture  
- Perimeter  
- Area  
- Smoothness  

The target variable classifies tumors as **Benign** or **Malignant**.

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Gradio  
- Dill (for model serialization)  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 🧠 Model Overview
This project applies **supervised machine learning (classification)** techniques to analyze medical data and predict cancer type.  
The dataset is preprocessed through scaling and feature selection to improve model performance.

---

## 🤖 Algorithms Used
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest Classifier  

The best-performing model was selected based on evaluation metrics and saved using **`dill`** for deployment.

---

## 💾 Model Persistence
The trained model is serialized using the **`dill` library**, allowing efficient saving and loading of the model for use within the Gradio web application.

---

## 📈 Model Evaluation
The model was evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  

The final model demonstrates strong and reliable performance on unseen test data.

---

## ▶️ How to Run the Project Locally

1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
<img width="1918" height="918" alt="image" src="https://github.com/user-attachments/assets/162791fb-e352-4f69-b3ed-0f6b652856fa" />
<img width="1918" height="912" alt="image" src="https://github.com/user-attachments/assets/81a5d977-e950-4e27-8edd-03d422d37788" />
