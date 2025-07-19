## 💧 WaterNet
WaterNet is a Cyber-Physical System (CPS) integrated with Machine Learning and LoRa communication to monitor and assess the quality of water for drinking and irrigation purposes. This system automates the collection, transmission, and prediction of water quality data to ensure safety and sustainability.

📄 Based on:
IEEE Transactions on Machine Learning
Volume 10, Issue Date: 03 May 2022

---

## 📊 Project Highlights
📡 LoRa-based IoT data transmission

🤖 Machine Learning model for water quality prediction

🌱 Assessment for both drinking and irrigation needs

⚙️ Structured and scalable monitoring network

🔢 Predicts water class using Water Quality Index (WQI)

---

## 🧠 Keywords
Cyber Physical System 

• LoRa 

• Drinking Water

• Irrigation Water

• Machine Learning

• Water Quality Index

• Water Monitoring Network

---

## 📁 Dataset Overview
The dataset contains samples of water quality across different regions, along with physical and chemical parameters.

## 🧾 Features:

Feature	Description

RID	Record ID

State	State of sampling

District_Name	District

Place_Name	Specific location

ph	Acidity/alkalinity level

Hardness	Calcium and magnesium levels

Solids	Total dissolved solids

Chloramines	Chlorine content

Sulfate	Sulfate concentration

Conductivity	Electrical conductivity

Organic_carbon	Organic compounds present

Trihalomethanes	Disinfection byproducts

Turbidity	Cloudiness of water

Prediction	Final classification (Safe/Unsafe)

---

## ⚙️ How to Use

## 🔧 1. Clone the repository:

bash

Copy

Edit

git clone https://github.com/hasina1674/WaterNet.git

cd WaterNet

## 🧪 2. Install dependencies:

bash

Copy

Edit

pip install -r requirements.txt

## 🚀 3. Run prediction:

bash

Copy

Edit

python src/predict_quality.py --input data/assessing_water_quality.csv

## 📈 4. (Optional) Run Jupyter notebook:

bash

Copy

Edit

jupyter notebook notebooks/water_quality_analysis.ipynb

---


## 🧠 Model & Methodology
Uses supervised learning (Random Forest / SVM / XGBoost)

Trained on physicochemical parameters

Evaluated using Accuracy, F1-score, and Confusion Matrix

---

## 📸 Sample Output

<img width="1919" height="918" alt="Screenshot 2025-04-18 222046" src="https://github.com/user-attachments/assets/8ffe7623-990a-412a-b3aa-836aa0bd0ad1" />

<img width="1895" height="906" alt="Screenshot 2025-04-19 093033" src="https://github.com/user-attachments/assets/8fef079a-ef58-4b73-8257-c5ca46a17340" />

<img width="1853" height="883" alt="Screenshot 2025-04-19 093106" src="https://github.com/user-attachments/assets/d6997a0d-c89d-484b-89cf-35cba7f3459d" />

Place_Name: Hyderabad

Prediction: Suitable for Drinking

Place_Name: Nashik

Prediction: Not Suitable for Irrigation

---
