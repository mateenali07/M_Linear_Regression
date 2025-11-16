# M_Linear_Regression
This project contains a Multiple Linear Regression model that predicts Sales based on TV, Radio, and Newspaper advertising budgets.  The model is trained in Jupyter Notebook and saved as a .sav file for easy reuse.  Includes data preprocessing, model training, evaluation, and prediction.
# 📊 Sales Prediction using Multiple Linear Regression

This project builds a **Multiple Linear Regression** model to predict **Sales** using advertising budgets spent on **TV**, **Radio**, and **Newspaper**.  
The model is trained in **Jupyter Notebook** and exported as a `.sav` file for easy reuse.

---

## 📁 Project Structure

```
Multiple-Linear-Regression/
│
├── data/
│   └── advertising.csv               # Dataset (optional)
│
├── notebook/
│   └── Multiple_Linear_Regression.ipynb   # Jupyter Notebook
│
├── model/
│   └── Multiple_Linear_Regression.sav     # Trained Model File
│
├── requirements.txt
└── README.md
```

---

## 🧠 About the Model

**Multiple Linear Regression** is a machine learning technique used to predict a continuous output based on multiple input features.

### **Input Features**
- TV Advertising Budget  
- Radio Advertising Budget  
- Newspaper Advertising Budget  

### **Target Variable**
- Sales  

This model helps identify which advertising channel contributes most effectively to increase sales.

---

## 🚀 How to Use This Project

### **1. Clone this repository**
```
git clone https://github.com/mateenali07/Multiple-Linear-Regression.git
```

### **2. Install dependencies**
```
pip install -r requirements.txt
```

### **3. Load and use the trained model**
```
import joblib

model = joblib.load("model/Multiple_Linear_Regression.sav")

prediction = model.predict([[TV_value, Radio_value, Newspaper_value]])
print("Predicted Sales:", prediction[0])
```

---

## 📈 Results & Insights

- Shows the impact of advertising budget on sales  
- Identifies the strongest predictors  
- Evaluation metrics and visualization included inside the notebook  

---

## 🛠 Technologies Used
- Python  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Scikit-learn    

---

## 👤 Author

**Mateen Ali**  
Python & Machine Learning Learner  
Passionate about Regression Models & Data Analysis  

---

## ⭐ Support

If you like this project, please **star ⭐ the repository**!

