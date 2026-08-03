# 🌸 Iris Species Classification using Logistic Regression

A beginner-friendly Machine Learning project that classifies Iris flower species based on sepal and petal measurements using Logistic Regression.

---

## 📌 Project Overview
The objective of this project is to build a multi-class classification model to predict the exact species of an Iris flower (`setosa`, `versicolor`, or `virginica`) using its physical features (sepal length, sepal width, petal length, and petal width).

---

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning Model:** Scikit-Learn (Logistic Regression, StandardScaler, Train-Test Split)

---

## 🚀 Step-by-Step Implementation Flow
1. **Data Loading & Preprocessing:** Loaded the classic Iris dataset, checked data shapes, and split the data into training (80%) and testing (20%) sets.
2. **Feature Scaling:** Standardized the features using `StandardScaler` to ensure optimal model performance.
3. **Model Training:** Trained a `LogisticRegression` model, which handles multi-class classification effectively.
4. **Model Evaluation:** Evaluated performance using Accuracy Score, Confusion Matrix Heatmap, and Classification Report (Precision, Recall, F1-Score).
5. **Live Prediction:** Tested the trained model with custom flower measurements to output real-time predictions with confidence scores.

---

## 📊 Results & Key Metrics
* **Model Accuracy:** High accuracy achieved on test data.
* **Confusion Matrix:** Visualized class-wise performance and correctly distinguished between different Iris flower varieties.

---

## 📂 Project Structure
```text
├── Iris_Species_Classification.ipynb   # Complete Google Colab Jupyter Notebook
└── README.md                           # Project Documentation
