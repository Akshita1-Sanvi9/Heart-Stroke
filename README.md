# 🫀 Heart Stroke Risk Predictor

A machine learning web app that predicts whether a person has a **high or low risk of heart stroke** based on health parameters.

> ⚠️ This is a learning project, not a medical tool. Do not use it for actual medical decisions.

## 🚀 Live Demo
👉 [Try the app](https://master-dgq7untgwoq4uqyxfieuy2.streamlit.app/)

## 🧠 How It Works
Enter a few health inputs and the model returns a risk prediction — High or Low.

Built using:
- **Logistic Regression** for classification
- **StandardScaler** for feature scaling
- **Streamlit** for the frontend

## 📁 Project Structure

```
Heart-Stroke/
├── app.py                  # Streamlit frontend
├── LogReg_heart_model.pkl  # Trained model
├── heart_scaler.pkl        # Scaler
├── heart_columns.pkl       # Feature columns
└── requirements.txt
```

## ⚙️ Run Locally

```bash
git clone https://github.com/Akshita1-Sanvi9/Heart-Stroke.git
cd Heart-Stroke
pip install -r requirements.txt
streamlit run app.py
```

## 🛠️ Tech Stack
Python · Scikit-learn · Streamlit · Pandas
