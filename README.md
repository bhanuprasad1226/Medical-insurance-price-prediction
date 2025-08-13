# 🏥 Medical Insurance Price Prediction
A web application that predicts medical insurance prices based on user input using **machine learning, FastAPI, Tailwind CSS,** and **JavaScript.**

Users can input personal and demographic details, and the app predicts their estimated insurance charges.
## ✨ Features
- Dynamic prediction using a trained machine learning model.

- Responsive design built with Tailwind CSS.

- User-friendly interface with interactive input fields.

- FastAPI backend serving predictions in real-time.

- Input parameters:
    - Age

    - Gender

    - BMI

    - Number of children

    - smoker status

    - Region
## 🌐 Live Demo
[▶ Try the Medical Insurance Price Predictor Online](https://medical-insurance-price-prediction-dsyf.onrender.com/)
## 📂 Project Structure
```bash
Medical-insurance-price-prediction/
│
├── app.py           # FastAPI application
├── model.pkl        # Trained ML model
├── templates/
│   └── index.html   # Frontend HTML
└── requirements.txt # Python dependencies

```
## 🚀 Getting Started
**1️⃣ Clone the repository**
```bash
git clone https://github.com/bhanuprasad1226/Medical-insurance-price-prediction.git
cd Medical-insurance-price-prediction
```
**2️⃣ Install dependencies**
```bash
pip install -r requirements.txt
```
**3️⃣ Run the application**
```bash
uvicorn app:app --reload
```
- Open your browser at `http://127.0.0.1:8000/`
  
**4️⃣ Input Parameters**
  
Fill in the form with:

- Age

- Gender

- BMI

- Number of children

- Smoker (Yes/No)

- Region (Northwest, Northeast, Southeast, Southwest)
  
The app will return the predicted insurance price instantly.
## 🛠 Technologies Used
- **Python & FastAPI** – Backend API and model integration.

- **Machine Learning (scikit-learn)** – Model trained to predict insurance charges.

- **Tailwind CSS** – Responsive and modern UI design.

- **JavaScript** – Frontend interaction and dynamic data display.


