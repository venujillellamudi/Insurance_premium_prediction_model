# Health Insurance Cost Predictor

A Machine Learning web application that predicts **Health Insurance Costs** based on user details such as age, income, BMI category, medical history, and lifestyle habits.

This project is built using **Python** and **Streamlit** to provide an interactive interface for users to input their information and receive a predicted insurance cost.

---

## 📌 Project Overview

Health insurance companies calculate premiums based on several personal and health-related factors.
This project uses a **machine learning model** to estimate insurance costs based on inputs such as:

* Age
* Number of dependants
* Income
* Genetic risk
* BMI category
* Smoking status
* Medical history
* Region
* Employment status
* Insurance plan

The application collects these inputs through a **Streamlit UI** and returns a predicted insurance cost.

---

## 🚀 Features

* Interactive **Streamlit web interface**
* User-friendly input form
* Machine learning based prediction
* Supports multiple health and lifestyle parameters
* Instant insurance cost prediction

---

## 🛠️ Technologies Used

* Python
* Streamlit
* Machine Learning
* Pandas
* Scikit-learn

---

## 📂 Project Structure

```
├── main.py                # Streamlit application
├── prediction_helper.py   # Prediction logic using ML model
├── model.pkl              # Trained machine learning model
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation
```

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/health-insurance-cost-predictor.git
```

2. Navigate to the project directory

```bash
cd health-insurance-cost-predictor
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit app:

```bash
streamlit run main.py
```

The application will open in your browser.

---

## 📊 Input Parameters

The prediction model considers the following parameters:

* Age
* Number of Dependants
* Income (in Lakhs)
* Genetic Risk
* Insurance Plan (Bronze / Silver / Gold)
* Employment Status
* Gender
* Marital Status
* BMI Category
* Smoking Status
* Region
* Medical History

---

## 📈 Output

The application predicts:

**Estimated Health Insurance Cost**

based on the provided inputs.

---

## 💡 Future Improvements

* Improve model accuracy
* Deploy the application online
* Add visualizations and analytics
* Integrate real insurance datasets

---

## 👨‍💻 Author

Developed as part of a **Machine Learning learning project**.

---
