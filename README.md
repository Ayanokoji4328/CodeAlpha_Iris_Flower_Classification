# 🌸 Iris Flower Classification

This project demonstrates the application of supervised machine learning to classify iris flowers into one of three species based on physical measurements.

---

## 🎯 Task Objectives

✔️ Use measurements of Iris flowers (*setosa*, *versicolor*, *virginica*) as input data  
✔️ Train a machine learning model to classify the species  
✔️ Use libraries like **Scikit-learn** for dataset access and model building  
✔️ Evaluate the model’s accuracy and performance on test data  
✔️ Understand basic **classification concepts** in machine learning

---

## 📘 Dataset Overview

The dataset consists of 150 samples with 4 features:
- `SepalLengthCm`
- `SepalWidthCm`
- `PetalLengthCm`
- `PetalWidthCm`

The target variable is `Species`, which includes:
- *Iris-setosa*
- *Iris-versicolor*
- *Iris-virginica*

- *Dataset-Link: * https://www.kaggle.com/datasets/saurabh00007/iriscsv
---

## 🚀 Project Workflow

1. Load and explore the dataset
2. Preprocess the data
3. Train a **Logistic Regression** model
4. Evaluate using metrics like accuracy and confusion matrix
5. Visualize insights with Seaborn

---

## 📊 Exploratory Data Analysis

We used Seaborn's `pairplot` to visualize feature relationships, colored by species:

- ✅ *Iris-setosa* is clearly distinguishable from the others
- ⚠️ Some overlap exists between *versicolor* and *virginica*
- ⭐ Petal features (length & width) offer the **best class separation**

<p align="center">
  <img src="download.png" alt="Iris Pairplot" width="600"/>
</p>

---

## 🧪 Model Performance

- **Model Used**: Logistic Regression
- **Test Accuracy**: ~97%
- **Evaluation Metrics**: Classification report and confusion matrix

---



