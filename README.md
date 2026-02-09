# California House Price Prediction using Machine Learning

## 📌 Overview
This project predicts **median house prices in California** using supervised machine learning techniques.  
The goal is to understand how socioeconomic and geographic factors influence housing prices and to compare baseline and advanced regression models.

---

## 🧠 Problem Statement
Predict the median house value for a given California region based on features such as income level, house age, population, and location.

---

## 📊 Dataset
- **California Housing Dataset** from `sklearn.datasets`
- Contains census data from California districts
- Target variable: **Median house price**

### Features
- Median Income  
- House Age  
- Average Rooms  
- Average Bedrooms  
- Population  
- Average Occupancy  
- Latitude  
- Longitude  

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  

---

## 🤖 Models Implemented
### 1. Linear Regression
- Used as a baseline model
- Simple and interpretable

### 2. XGBoost Regressor
- Tree-based ensemble model
- Captures non-linear relationships
- Outperforms the baseline model

---

## 📈 Evaluation Metrics
- **R² Score** – Explained variance  
- **Mean Absolute Error (MAE)** – Average prediction error  
- **Root Mean Squared Error (RMSE)** – Penalizes large errors  

---

## 🔍 Results
- XGBoost achieved better performance than Linear Regression
- Demonstrates the effectiveness of boosting methods on housing data

---

## 🧪 Model Inference
The trained model supports predictions on **custom input values**, allowing estimation of house prices for unseen data.

---

## ⚠️ Limitations
- Based on historical census data
- Real-world market dynamics are not fully captured
- Performance can be improved with further tuning

---

## 🚀 Future Work
- Hyperparameter optimization
- Cross-validation
- Model deployment using Flask or FastAPI

---

## 👨‍💻 Author
**Akhil Reddy**  
Mechanical Engineering (Dual Degree) | Aspiring AI Engineer
