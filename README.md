# AgroEye-ML-Crop-Health-Predictor
Smart crop health prediction using Random Forest and agricultural data. Built with Python, Gradio, and Scikit-learn.

# 🌾 AgroEye – Smart Crop Health Monitoring using Machine Learning

**AgroEye** is a machine learning-powered tool that predicts the health status of soybean crops using key physiological and biochemical indicators.

It helps farmers and agricultural researchers make data-driven decisions by offering:

- 🌱 Health prediction of crops
- 📈 Yield-based classification
- 🔬 Analysis of plant traits
- 🧠 AI-powered model using Random Forest
- 🖥️ Interactive web UI via Gradio

> ⚡ Built using **Scikit-learn**, **Gradio**, **Pandas**, and real agricultural data

---

## 🔍 Features

- ✅ Predicts whether a soybean crop is **Healthy** or **Unhealthy**
- 📊 Based on features like plant height, sugars, protein content, and chlorophyll levels
- 🧪 Uses median seed yield to define crop health label
- 🧠 Trained using RandomForestClassifier
- 🖼️ Visual evaluation with confusion matrix and accuracy score
- 💬 User-friendly Gradio interface for real-time prediction

---

## 🌾 Dataset Info

- 🎯 **Advanced Soybean Agricultural Dataset**
- 🌿 Target: `health_status` (1 = Healthy, 0 = Unhealthy)
- 📏 Label created using median of "Seed Yield per Unit Area (SYUA)"

---

## 🧬 Features Used for Prediction

- 📏 Plant Height (PH)  
- 🌾 Number of Pods (NP)  
- ⚖️ Biological Weight (BW)  
- 🍬 Sugars (Su)  
- 💧 Relative Water Content in Leaves (RWCL)  
- 🌿 Chlorophyll A (663 nm)  
- 🌿 Chlorophyll B (649 nm)  
- 🧪 Protein Percentage (PPE)  
- 🌰 Weight of 300 Seeds (W3S)  
- 🍃 Leaf Area Index (LAI)  
- 🌱 Number of Seeds per Pod (NSP)  
- 🧬 Protein Content (PCO)

---

## 🛠️ Tech Stack

- 🐍 Python (Google Colab)
- 🔍 Scikit-learn
- 📊 Pandas, NumPy
- 📈 Seaborn, Matplotlib
- 🧠 Random Forest Classifier
- 🖥️ Gradio (for UI)
