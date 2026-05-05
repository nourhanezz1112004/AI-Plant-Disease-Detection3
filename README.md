# 🌿 AI Precision Agriculture System

### Intelligent Systems Project – Plant Disease Detection & Decision Support

---

##  Overview

This project presents an **AI-powered intelligent system** designed to support **precision agriculture**.
It helps farmers and agricultural researchers **detect plant diseases early**, **analyze crop health**, and **make data-driven decisions** to improve productivity and sustainability.

The system integrates:

* Deep Learning for image classification
* Explainable AI (Grad-CAM)
* Web-based dashboard for real-time interaction

---

##  Objectives

* Detect plant diseases using image-based deep learning models
* Provide **confidence scores** for predictions
* Visualize model decisions using **Grad-CAM heatmaps**
* Offer **basic recommendations** for crop management
* Build a usable **web platform** for non-technical users

---

##  Intelligent System Components

### 1. AI-Based Decision Support System

* Predicts plant disease from uploaded images
* Assists farmers in taking early action

### 2. Explainable AI (Grad-CAM)

* Highlights infected areas in plant leaves
* Improves trust and interpretability

### 3. Web Application Interface

* Upload plant images بسهولة
* View predictions instantly
* Compare original vs heatmap

---

##  System Architecture

```text
User → Upload Image → Flask Backend → AI Model → Prediction
                                      ↓
                                Grad-CAM Generator
                                      ↓
                          Web Interface (Results Display)
```

---

##  Technologies Used

*  Python
*  TensorFlow / Keras
*  Flask
*  OpenCV
*  HTML / CSS / Bootstrap

---

##  Features

*  Plant Disease Detection
*  High Confidence Prediction
*  Grad-CAM Visualization
*  User-Friendly Interface
*  Real-Time Image Processing
*  Decision Support Output

---

##  Example Output

```
Prediction: Tomato___Late_blight  
Confidence: 99.97%

Recommendation:
Remove infected leaves and apply fungicide treatment.
```

---

##  Project Structure

```
plant_ai_app/
│
├── app.py
├── model.keras
├── class_names.json
├── requirements.txt
│
├── static/
│   ├── uploads/
│   └── gradcam/
│
├── templates/
│   ├── index.html
│   └── result.html
│
└── README.md
```

---

##  How to Run Locally

```bash
git clone https://github.com/nourhanezz1112004/AI-Plant-Disease-Detection.git
cd AI-Plant-Disease-Detection

pip install -r requirements.txt
python app.py
```

Then open:

```
http://127.0.0.1:5000
```

---

##  Deployment

This project can be deployed on platforms like:

* Render
* Railway
* Heroku

---

##  Future Improvements

* Integration with IoT sensors (soil moisture, temperature)
* Automated irrigation control
* Crop growth simulation
* Weather & market data integration
* Mobile application version

---

##  Course Information

**Course:** Intelligent Systems (CS481)
**Instructor:** Dr. Noha El-Showly

---

##  Impact

This system demonstrates how AI can:

* Increase agricultural productivity
* Reduce crop loss
* Enable smart farming decisions
* Support sustainable agriculture

---

##  If you like this project

Give it a star on GitHub ⭐
