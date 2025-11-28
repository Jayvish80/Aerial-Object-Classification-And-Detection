# Aerial-Object-Classification-And-Detection
"Aerial Object Classification &amp; Detection system using Deep Learning. Classifies Bird vs Drone images with CNN &amp; Transfer Learning and supports YOLOv8-based real-time detection. Includes preprocessing, model training, evaluation, and Streamlit deployment for interactive predictions."


# Aerial Object Classification & Detection

A Deep Learning–based project that classifies **Bird vs Drone** images and performs **real-time object detection** using **YOLOv8**. Designed for aerial surveillance, wildlife monitoring, and airspace security. Includes Streamlit deployment for interactive predictions.

---

## 🚀 Project Overview
This project builds an AI system capable of:

- Classifying aerial images into **Bird** or **Drone**
- Detecting objects using **YOLOv8**
- Deploying the final model using **Streamlit**

The solution is optimized for real-time surveillance and critical decision-making.

---

## 📌 Problem Statement
Aerial monitoring systems often misidentify birds and drones, leading to false alarms or security risks.  
This project applies **Deep Learning** to accurately identify and detect objects from aerial images, improving airspace safety and wildlife monitoring.

---

## 🧠 Skills & Technologies
- Deep Learning  
- CNN & Transfer Learning  
- YOLOv8 Object Detection  
- Python  
- TensorFlow / Keras / PyTorch  
- Streamlit  
- Data Augmentation  
- Model Evaluation  

---

## 📂 Dataset Details

### Classification Dataset
- Classes: **Bird**, **Drone**
- Format: `.jpg`
- Train: 1414 bird / 1248 drone  
- Valid: 217 bird / 225 drone  
- Test: 121 bird / 94 drone  

### YOLOv8 Detection Dataset
- 3319 images + annotation `.txt` files  
- Train: 2662  
- Val: 442  
- Test: 215  

---

## 🛠 Workflow

### 1. Data Preprocessing
- Resize (224×224)  
- Normalize (0–1)  
- Augment images  

### 2. Model Building
- Custom CNN  
- Transfer Learning models:  
  - ResNet50  
  - MobileNet  
  - EfficientNetB0  

### 3. Training
- EarlyStopping  
- ModelCheckpoint  

### 4. Evaluation
- Accuracy  
- Precision/Recall  
- F1-score  
- Confusion Matrix  

### 5. YOLOv8 Detection
- Train YOLO model  
- Validate & Test  
- Predict on new images  

### 6. Streamlit Deployment
- Upload image  
- Get prediction + confidence  
- Display YOLO detection results  

---

## 📊 Applications
- Security Surveillance  
- Anti-Drone Systems  
- Wildlife Monitoring  
- Airport Bird-Strike Prevention  
- Environmental Research  

