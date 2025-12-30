# Algerian_forest_fires_FWI_prediction
# Regression Model Web Application

## 📌 Overview
This project is an end-to-end machine learning regression application.  
It covers the complete workflow starting from data analysis and model training to deploying the trained model with a simple HTML frontend integrated with a Python backend.

---

## 🧠 Project Workflow
1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature scaling
3. Regression model training and evaluation
4. Saving trained model and scaler using pickle
5. Backend integration using Python
6. Frontend interaction using HTML

---

## 📂 Project Structure
---

## 📊 Dataset
- The dataset is stored in the `dataset/` directory
- Used for exploratory analysis and model training
- Basic cleaning and preprocessing were performed during EDA

---

## 📓 Notebooks
- **01_EDA.ipynb**  
  - Data understanding and visualization  
  - Missing value handling  
  - Feature analysis and insights  

- **02_Model_Training.ipynb**  
  - Feature selection  
  - Train-test split  
  - Ridge Regression model training  
  - Model evaluation  
  - Saving trained model and scaler  

---

## 🤖 Machine Learning Model
- Algorithm: **Ridge Regression**
- Feature Scaling: **StandardScaler**
- Model Persistence: **Pickle (`.pkl`)**

Saved files:
- `ridge.pkl` – trained regression model  
- `scaler.pkl` – fitted scaler used for preprocessing  

---

## 🎨 Frontend
- A simple HTML-based frontend (`index.html`)
- Allows user input for prediction
- Integrated directly with the Python backend (`model.py`)
- Displays prediction results to the user

---

## ⚙️ Backend
- Implemented using Python
- Loads trained model and scaler from `.pkl` files
- Handles prediction logic and frontend interaction

---

## 🚀 How to Run the Project

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
2 Run the backend

Bash

python application.py

Copy code

3 Open frontend

Open frontend/index.html in a web browser (or access via backend route if configured)
The trained regression model successfully predicts target values based on user input using the saved model and scaler.
