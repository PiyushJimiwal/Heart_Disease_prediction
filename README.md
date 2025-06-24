# ❤️ Heart Disease Prediction using Neural Networks

This project uses machine learning to predict the presence of heart disease in patients based on various medical attributes. A neural network model has been trained on the **Cleveland Heart Disease dataset** and achieves an accuracy of **88%**.

---

## 📌 Project Highlights

- ✅ Dataset: [Heart Disease - Cleveland UCI Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- ✅ Model: Neural Network built with TensorFlow/Keras
- ✅ Accuracy: **88%**
- ✅ Language: Python
- ✅ Preprocessing: Missing value handling, encoding, and scaling
- ✅ Evaluation: Accuracy, loss curves

---

## ⚙️ Model

- Framework: **TensorFlow / Keras**
- Type: Feedforward Neural Network
- Preprocessing:
  - Replaced missing values with `NaN` then filled with column **medians**
  - One-hot encoding for categorical features
  - Feature scaling using `StandardScaler`

## 📊 Features Used
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Serum Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- ST depression induced by exercise
- Slope of peak exercise ST segment
- Number of major vessels
- Thalassemia

---

## License
This project is licensed under the [MIT License](LICENSE).


## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/PiyushJimiwal/Heart_Disease_prediction.git
   cd Heart_Disease_prediction
