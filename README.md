# 🏡 Housing Price Prediction  

This notebook demonstrates a **machine learning project** to predict housing prices using synthetic data.  
It is designed as a **portfolio project** to highlight ML skills, model building, and interpretability for internship applications.  

---

## 🎯 Motivation  
Predicting housing prices is a **real-world problem** with practical applications for buyers, sellers, and real estate companies.  
This project demonstrates the full ML workflow: from **data preprocessing → modeling → evaluation → interpretability → visualization**.  

---

## ⚙️ Key Features  
- **Data Generation** → Synthetic dataset with 10 features.  
- **Neural Network Regression** → Implemented with TensorFlow/Keras.  
- **Model Evaluation** → R² Score & MAE metrics.  
- **Baseline Models** → Linear Regression & Random Forest for comparison.  
- **Visualization** → Interactive plots using Plotly.  
- **Interpretability** → Feature importance analysis with SHAP.  

---

## 📊 Results  

| Model             | R² Score | MAE        |
|-------------------|----------|------------|
| Neural Network    | 0.871    | 45077.97   |
| Linear Regression | 0.998    | 5230.38    |
| Random Forest     | 0.981    | 17173.65   |

✅ Linear Regression achieved the **best performance** with R² ≈ 0.998.  
✅ Neural Network & Random Forest also performed strongly, showing robust predictions.  

---

## 📈 Visualizations  

- **Actual vs Predicted Prices** (Neural Network) → Interactive scatter plot with regression line.  
- **SHAP Summary Plot** → Feature contributions across test set.  
- **SHAP Force Plot** → Individual prediction explainability.  

*(Notebook contains all visualizations; static examples can be added here as screenshots.)*  

---

## 🛠️ Tech Stack  

- **Python 3**  
- **Pandas, NumPy** → Data preprocessing  
- **Scikit-learn** → Linear Regression, Random Forest, evaluation metrics  
- **TensorFlow / Keras** → Neural Network model  
- **Plotly** → Interactive visualizations  
- **SHAP** → Model interpretability  

---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/Housing-Price-Prediction.git
