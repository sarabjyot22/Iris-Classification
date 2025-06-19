# 🌸 Iris Classification Project

This repository contains a complete machine learning pipeline for classifying iris flowers into their respective species — *Setosa*, *Versicolor*, and *Virginica* — using Python and Scikit-learn. The project covers data preprocessing, exploratory data analysis (EDA), model training, evaluation, and reporting.

---

## 📁 Project Structure

📦 iris-classification-project/
├── Iris.csv # Dataset file
├── Iris_Classification_Project.ipynb # Jupyter Notebook with code
├── Iris_Classification_Project_Report.docx # Project report
├── README.md # Project documentation (this file)


---

## 📌 Problem Statement

To build a supervised classification model that accurately predicts the species of an iris flower based on:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

---

## 🧰 Technologies Used

- **Language:** Python  
- **Tools:** Jupyter Notebook, VS Code  
- **Libraries:**  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  
  - `scikit-learn`

---

## 📊 Steps Involved

### 1. Data Preprocessing
- Removed unnecessary `Id` column.
- Handled missing values (none found).
- Encoded `Species` labels using `LabelEncoder`.
- Standardized features using `StandardScaler`.

### 2. Exploratory Data Analysis
- Visualizations: Pairplot, Heatmap, Boxplot, Histograms.
- Correlation analysis for feature importance.

### 3. Model Building
Trained the following classification algorithms:
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

### 4. Model Evaluation
- Evaluated using accuracy, precision, recall, F1-score.
- Confusion Matrix plotted using Seaborn.
- 5-fold Cross-Validation used on Random Forest.

---

## 📈 Results

- **Random Forest** delivered the highest accuracy and generalization performance.
- **Petal Length** and **Petal Width** were most influential for classification.
- All models showed strong results with minimal misclassification.

---

## 🚀 Optional Deployment

You can deploy the model using:
- **Flask** or **Django** for a web-based prediction app.
- User interface to input features and get species prediction.

---
