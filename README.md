# 🌿 XAI Plant Disease Detection using Deep Learning + FastAPI

An intelligent web-based system that detects **plant leaf diseases** using a **Convolutional Neural Network (CNN)** and explains predictions using **Grad-CAM (Explainable AI)**.

This project helps in **early disease diagnosis**, crop protection, and smarter agriculture using AI.

---

## 🍃 Repository

### 📌 GitHub Repo
`xai-plant-disease-detection`

### 📁 Get Jupyter Notebook + Keras Model File:  
https://drive.google.com/drive/folders/19DNtBwh-G0flFeckGob47MXi4yJJjCFm?usp=sharing

### 🌐 Live Demo
https://huggingface.co/spaces/ShreyaGupta90/xai_plant_disease_detection

---

## 📌 Project Overview

This system analyzes uploaded plant leaf images and performs:

- Disease Detection  
- Confidence Score  
- Severity Estimation  
- Treatment Suggestion  
- Prevention Advice  
- Explainable AI Visualization (Grad-CAM)

The model helps farmers, students, and researchers identify diseases quickly through image-based diagnosis.

---

## 🧠 Key Features

- 🌿 Plant leaf disease classification  
- 🧠 Deep Learning CNN model
- 🔥 Grad-CAM Explainable AI heatmap  
- 📊 Prediction confidence percentage  
- 🌡 Disease severity estimation  
- 💊 Treatment recommendation  
- 🛡 Prevention guidance  
- 🌐 FastAPI web deployment  
- 📱 Responsive clean UI  

---

## 🛠️ Tech Stack

- Python  
- TensorFlow / Keras  
- CNN (Custom Architecture)  
- OpenCV  
- NumPy  
- PIL  
- FastAPI  
- Uvicorn  
- Hugging Face Spaces  
- Jupyter Notebook / Colab  

---

## 🤖 CNN Architecture Summary

- Conv2D Layers → Feature Extraction  
- ReLU Activation  
- MaxPooling2D → Downsampling  
- Flatten Layer  
- Dense Layers  
- Dropout Regularization  
- Softmax Output (38 Classes)

**Optimizer:** Adam  
**Loss Function:** Sparse Categorical Crossentropy

---

## 📂 Workflow

1. Collect & preprocess plant leaf dataset  
2. Train CNN model on disease classes  
3. Save trained model (`best_model.keras`)  
4. Build FastAPI frontend  
5. Integrate model with prediction API  
6. Add Grad-CAM explainability  
7. Deploy publicly on Hugging Face  

---

## 📊 Dataset Highlights

- 📁 87K+ Leaf Images  
- 🌿 Multiple Crops Included  
- 🦠 38 Disease / Healthy Classes  

### Example Classes

- Tomato Early Blight  
- Tomato Late Blight  
- Apple Scab  
- Grape Black Rot  
- Potato Late Blight  
- Healthy Leaves  

---

## 🔥 Explainable AI (Grad-CAM)

Grad-CAM highlights image regions used by CNN during prediction.

### Color Meaning

- 🔴 Red / Yellow → High Attention  
- 🟢 Green → Medium Attention  
- 🔵 Blue → Low Attention  

This improves trust, transparency, and interpretability.

---

## 💻 Web App Output

Upload Leaf Image → Predict Disease

Outputs include:

- Disease Name  
- Confidence %  
- Severity  
- Treatment  
- Prevention  
- Original Image  
- Grad-CAM Heatmap  

---

## 🧠 main.py Output (FastAPI UI)

<img width="1920" height="1020" alt="Screenshot 2026-04-23 001925" src="https://github.com/user-attachments/assets/fb8907f2-4164-4ea9-a66a-acc7774cb0cd" />
<img width="1920" height="1020" alt="Screenshot 2026-04-23 002012" src="https://github.com/user-attachments/assets/64011e73-d807-4f3f-ac27-37e4601cf1b9" />

---

## 🚀 Future Enhancements

- 📱 Android / iOS mobile app
- 🌍 Multilingual farmer support
- 📷 Real-time camera detection
- ☁ Cloud database reports
- 📍 Geo-based disease alerts
- 🤖 Better transformer models
- 🌿 Fertilizer recommendation module
  
---

## 🏆 Why This Project Stands Out

- Real-world agriculture problem solving
- Deep Learning implementation
- Explainable AI integration
- End-to-end deployment
- User-friendly interface
- Strong portfolio project for AI/ML roles
  
---

## 🙌 Author

  **Shreya Gupta**  
  Aspiring AI/ML Engineer | Deep Learning Enthusiast | AI for Impact

  ---

  ✨ *From Leaves to Learning 🍃*  
  ✨ *From Agriculture to Intelligence 🌍*  
  ✨ *AI that helps fields flourish. 🚀* 
  
---
