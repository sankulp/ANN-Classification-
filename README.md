# 💼 Customer Churn Prediction App

This project is an interactive web app built using **Streamlit** that predicts whether a bank customer is likely to churn based on key account and demographic data. It leverages a **Sequential Artificial Neural Network (ANN)** model built with TensorFlow and trained on real-world data.

---

## 🚀 Features

- Real-time churn prediction using a pre-trained ANN model
- Gender encoding via LabelEncoder
- Geography encoding via OneHotEncoder
- Feature scaling using StandardScaler
- Intuitive web interface powered by Streamlit
- **Model training visualized using TensorBoard**

---

## 🧠 Model Info

- **Model Type:** Sequential ANN (Keras + TensorFlow)
- **Frameworks Used:** TensorFlow, TensorBoard, scikit-learn
- **Target Variable:** `Exited` (1 = customer churned, 0 = customer retained)
- **Loss Function & Metrics:** Visualized using **TensorBoard** during training

**Input Features:**
- `CreditScore`
- `Geography`
- `Gender`
- `Age`
- `Tenure`
- `Balance`
- `NumOfProducts`
- `HasCrCard`
- `IsActiveMember`
- `EstimatedSalary`

---

## 📁 Project Structure


## 📁 Project Structure

├── app.py # Streamlit app source code
├── model.h5 # Trained ANN model (TensorFlow)
├── scaler.pkl # Pre-fitted StandardScaler object
├── label_encoder_gender.pkl # LabelEncoder for Gender column
├── onehot_encoder_geo.pkl # OneHotEncoder for Geography column
├── Churn_Modelling.csv # Dataset used for training
├── predictions.ipynb # Notebook to test model predictions
├── experiments.ipynb # Model training and evaluation
├── requirements.txt # Python dependencies
└── README.md # Project documentation
