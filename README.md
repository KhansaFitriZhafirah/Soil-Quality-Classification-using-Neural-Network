# 🌱 Soil Quality Classification and Crop Recommendation using Neural Network

A final project for the Artificial Intelligence course that implements a supervised learning approach with a **Neural Network (NN)** model to classify soil quality and recommend optimal crops based on physical and chemical soil parameters. We trained the model using a dataset containing essential soil parameters such as **nitrogen, phosphorus, potassium, temperature, humidity, pH, and rainfall**, then evaluated its performance in predicting crop suitability.

---

## 🎯 Project Objectives

- To develop a Neural Network model capable of classifying soil quality.
- To recommend optimal crops based on soil characteristics.
- To demonstrate the applicability of AI in agricultural decision-making.

---

## 🧪 Dataset Description

- Source: Kaggle – [Crop Recommendation Dataset]
- Features used:
  - **Nitrogen (N)**
  - **Phosphorus (P)**
  - **Potassium (K)**
  - **Temperature (°C)**
  - **Humidity (%)**
  - **pH Value**
  - **Rainfall (mm)**
- Target: Recommended **crop type** for each soil condition.

---

## ⚙️ Tools & Libraries

- **Language**: Python
- **Libraries**: NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow, Keras

---

## 🚀 Workflow Overview

1. **Data Preprocessing**
   - Handle missing values, duplicates, and outliers.
   - Normalize features using `StandardScaler`.
   - Encode crop labels using `LabelEncoder`.

2. **Model Development**
   - Build and train a Neural Network with tuned hyperparameters.
   - Apply `early_stopping` to avoid overfitting.
   - Optimize learning rate for minimal loss.

3. **Evaluation**
   - Assess model on test data.
   - Generate accuracy and loss metrics.
   - Visualize performance trends.

4. **Prediction Simulation**
   - Test the model with real or simulated soil data.
   - Predict suitable crops based on user input.

---

## 📊 Key Results

| Model Stage        | Accuracy (%) | Loss (%) |
|--------------------|--------------|----------|
| Initial Learning   | 94.55        | 21.37    |
| Final Model        | **97.95**    | **8.81** |

> The final model shows strong performance and generalization with high accuracy and low prediction error.

---

## 💡 Benefits for Agriculture

- **Faster decision-making**: Farmers can make informed crop choices instantly.
- **Cost efficiency**: Reduces reliance on traditional soil testing.
- **Sustainability**: Promotes optimal land use and resource management.
