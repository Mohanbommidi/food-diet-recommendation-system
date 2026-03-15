# 🍴 Food Diet Recommendation System

A **Machine Learning–based web application** that provides personalized diet recommendations based on user health details and goals.

This project helps users generate meal plans tailored to their **age, height, weight, dietary preferences, and fitness goals**.

---

## 🚀 Features

📊 **BMI Calculation** – Computes Body Mass Index and determines health condition.

🥗 **Personalized Meal Plans** – Provides recommendations for:

* Weight Loss
* Weight Gain
* Weight Maintenance

🥬 **Diet Preferences**

* Vegetarian
* Non-Vegetarian
* Mixed Diet

🍛 **Meal Customization**

* Select number of meals per day
* Customize meals based on available ingredients

🍽 **Default Indian Meal Plan**

* Pre-designed balanced diet for general users

📖 **Recipes & Instructions**

* Each recommended food item includes preparation steps.

⚡ **Interactive Frontend**

* Built with Streamlit for a simple and user-friendly interface.

🔗 **FastAPI Backend**

* Handles ML model predictions and API requests.

---

## 🛠 Tech Stack

**Programming Language**

* Python

**Frontend**

* Streamlit

**Backend**

* FastAPI

**Machine Learning**

* Scikit-learn (KNN Algorithm)

**Database**

* CSV / SQLite (Food dataset & nutritional values)

**Libraries**

* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📂 Project Structure

Food-Diet-Recommendation-System/

│
├── FastAPI_Backend/        # Backend with FastAPI + ML model
│   ├── main.py             # API routes
│   ├── model.pkl           # Trained ML model
│   └── requirements.txt

│
├── Streamlit_Frontend/     # Streamlit UI
│   ├── Hello.py            # Main Streamlit app
│   └── pages/              # Additional UI pages

│
├── Data/                   # Food dataset
│   └── food_data.csv

│
├── README.md               # Project documentation
└── LICENSE                 # License file

---

## ▶️ How to Run the Project

1️⃣ Install required libraries

pip install -r requirements.txt

2️⃣ Run the Streamlit app

streamlit run Hello.py

3️⃣ Open in browser

http://localhost:8501

---

## 📌 Future Improvements

* Add more food datasets
* Improve ML recommendation accuracy
* Deploy the application online
* Add user authentication

---
