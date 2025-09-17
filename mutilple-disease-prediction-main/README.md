

# 🩺 Multiple Disease Prediction System

A Machine Learning-based web application to predict the likelihood of **Diabetes**, **Heart Disease**, and **Parkinson's Disease** based on patient input data. This system is built to assist healthcare providers in early diagnosis and data-driven decision-making.

---

## 🚀 Features

* Predicts three major diseases using trained ML models:

  * **Diabetes**
  * **Heart Disease**
  * **Parkinson’s Disease**
* Web interface for user-friendly interaction using **Streamlit**
* Real-time disease prediction with results under **2 seconds**
* Trained on real-world datasets with accuracy ranging from **75% to 87%**
* Secure and efficient data handling

---

## 🛠️ Tech Stack

* **Languages & Tools:** Python, Pandas, Scikit-learn, Streamlit, NumPy, Pickle
* **ML Algorithms Used:** Logistic Regression, Support Vector Machine (SVM), Decision Tree
* **Preprocessing:** StandardScaler, Data Cleaning, Feature Selection
* **Deployment:** Streamlit (Local Web App)

---

## 📊 Dataset Information

1. **Diabetes Dataset:** 768 patient records with features like glucose, insulin, BMI, age
2. **Heart Disease Dataset:** 304 records including chest pain, cholesterol, blood pressure
3. **Parkinson’s Dataset:** 195 voice measurement records including frequency and jitter values

---

## 🔍 Accuracy Summary

| Disease       | Algorithm           | Accuracy (%) |
| ------------- | ------------------- | ------------ |
| Diabetes      | Logistic Regression | 75.3%        |
| Heart Disease | SVM                 | 86.9%        |
| Parkinson’s   | SVM & Logistic Reg. | 87.1%        |

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/multiple-disease-prediction.git
cd multiple-disease-prediction

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```

---

## 💡 How It Works

1. User selects the disease type (Diabetes / Heart / Parkinson’s)
2. Enters patient input parameters
3. The system processes input and predicts using a pre-trained model
4. Result is shown instantly along with disease status

---

## 📁 Project Structure

```
├── app.py
├── models/
│   ├── diabetes_model.sav
│   ├── heart_model.sav
│   └── parkinsons_model.sav
├── data/
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv
├── utils/
│   └── preprocessing.py
├── requirements.txt
└── README.md
```

---

## 👨‍⚕️ Use Cases

* Clinical decision support systems
* Educational demonstration of ML in healthcare
* Rapid health screening tools for remote care setups

---

## 🧠 Future Enhancements

* Add more diseases and datasets
* Integrate Explainable AI (XAI) methods
* Deploy on cloud (e.g., Heroku, AWS)
* Add authentication for secure usage

---
