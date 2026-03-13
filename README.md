# 🔥 Forest Fire Prediction Web App

A **Machine Learning web application built with Flask** that predicts forest fire risk based on environmental parameters such as temperature, humidity, wind speed, and rainfall.

The model uses a **Ridge Regression algorithm** trained on forest fire dataset features and deployed using **Flask**.

---

## 🤝 Contributors

This project was developed collaboratively by:

* **Soham** – Machine Learning Model & Flask Backend
* **Vedant** – Frontend Development & Support

---

## 🚀 Features

* Predict forest fire risk using Machine Learning
* Simple web interface for entering environmental data
* Uses **Ridge Regression model** for prediction
* Data preprocessing using **StandardScaler**
* Flask backend for serving predictions

---

## 🧠 Machine Learning Model

The model takes the following input features:

* Temperature
* Relative Humidity (RH)
* Wind Speed (Ws)
* Rain
* FFMC (Fine Fuel Moisture Code)
* DMC (Duff Moisture Code)
* ISI (Initial Spread Index)
* Classes
* Region

The input data is **scaled using StandardScaler** before making predictions.

---

## 🛠 Tech Stack

* Python
* Flask
* Scikit-learn
* NumPy
* Pandas
* HTML / CSS

---

## 📂 Project Structure

flask-ml-project
│
├── models
│   ├── ridge.pkl
│   └── scaler.pkl
│
├── templates
│   ├── index.html
│   └── home.html
│
├── application.py
├── requirements.txt
└── README.md

---

## ▶️ How to Run the Project

1. Clone the repository

git clone https://github.com/yourusername/flask-ml-project.git

2. Navigate to the project folder

cd flask-ml-project

3. Install dependencies

pip install -r requirements.txt

4. Run the Flask application

python application.py

5. Open your browser and go to

http://127.0.0.1:5000

---

## 📊 Prediction Workflow

1. User enters environmental parameters in the web form
2. Input data is scaled using **StandardScaler**
3. The trained **Ridge Regression model** predicts fire risk
4. The prediction result is displayed on the webpage

---

## 📌 Future Improvements

* Improve UI/UX of the web interface
* Add visualization dashboards
* Deploy the application online (Render / AWS / Heroku)
* Improve model performance with more data
