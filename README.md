# 🌸 Iris Species Classification using Logistic Regression

An end-to-end Machine Learning project that classifies Iris flower species based on sepal and petal measurements using **Logistic Regression**.

---

## 📌 Project Overview
The objective of this project is to build a multi-class classification model to accurately predict the exact species of an Iris flower (*setosa*, *versicolor*, or *virginica*) using its physical features. 

To ensure real-world authenticity and prevent unrealistic 100% overfitting, the model incorporates strategic train-test splitting, feature scaling (`StandardScaler`), and regularization parameters (`C=0.5`).

---

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning Framework:** Scikit-Learn

---

## 🚀 Step-by-Step Implementation Flow
1. **Dataset Loading & Generation:** Loads the classic Iris dataset from `scikit-learn` and structures it into a clean Pandas DataFrame.
2. **Exploratory Data Analysis (EDA):** Visualizes feature distributions and relationships using Seaborn pairplots.
3. **Data Preprocessing & Splitting:** Splits the data into training and testing sets (`test_size=0.3`) and applies feature standardization using `StandardScaler`.
4. **Model Training:** Trains a multi-class `LogisticRegression` model with regularization.
5. **Model Evaluation:** Evaluates performance using Accuracy Score (~95.56%), a detailed Classification Report (Precision, Recall, F1-Score), and a Confusion Matrix Heatmap.

---

## 📊 Results & Performance
* **Model Accuracy:** ~95.56% on test data, reflecting robust real-world generalization.
* **Confusion Matrix:** Clearly displays class-wise predictions and highlights minor misclassifications realistically.

---

## 📂 Project Structure
```text
├── iris_classification_data.csv        # Processed dataset file
├── Iris_Species_Classification.ipynb   # Complete Jupyter / Google Colab Notebook
└── README.md                           # Project Documentation
