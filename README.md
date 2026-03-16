# 🎓 Student Academic Performance Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict student academic performance using Machine Learning and Deep Learning techniques. The system analyzes different student-related factors such as study time, absences, and demographic attributes to predict whether a student will perform well or poorly in their final exams.

The goal of this project is to demonstrate how data science and machine learning can help identify patterns in student behavior and support educational decision-making.

---

## 📊 Dataset

The project uses the **Student Performance Dataset** which contains information about students’ academic records and personal attributes.

Key attributes include:

* Study time
* Absences
* Parental education
* Internet access
* Previous grades
* Final grade (G3)

Target Variable:

* **G3 – Final Grade**

Prediction Type:

* Classification (Good / Poor Performance)

---

## ⚙️ Technologies Used

Programming Language:

* Python

Libraries:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras

Development Environment:

* Google Colab

---

## 🧠 Machine Learning Models Implemented

### 1️⃣ Logistic Regression

Logistic Regression was used as a baseline model to classify students based on their likelihood of performing well. This model estimates the probability of student success based on input features.

### 2️⃣ Random Forest Classifier

Random Forest is an ensemble learning method that combines multiple decision trees to improve prediction accuracy. This model captured nonlinear relationships between student behaviors and academic outcomes.

### 3️⃣ Neural Network Model

A deep learning neural network was implemented with:

* Input Layer
* Two Hidden Layers
* Dropout Layers
* Output Layer

Training configuration:

* Optimizer: Adam
* Loss Function: Binary Cross Entropy

---

## 📈 Model Evaluation

The dataset was divided into:

* 70% Training Data
* 30% Testing Data

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve

---

## 📊 Visualizations

The project includes several visualizations:

* Grade Distribution
* Study Time vs Final Grade
* Absences vs Final Grade
* Correlation Heatmap
* Feature Importance
* Model Accuracy Comparison
* ROC Curve

---

## 🚀 Project Workflow

1. Data Loading
2. Data Preprocessing
3. Feature Encoding
4. Data Visualization
5. Train/Test Split
6. Model Training
7. Model Evaluation
8. Performance Comparison

---

## 📂 Project Structure

```
Student-Performance-ML/
│
├── Student_Performance_Project.ipynb
├── student-mat.csv
├── README.md
└── requirements.txt
```

---

## 🎯 Conclusion

This project demonstrates that machine learning models can effectively predict student academic performance. Among the models tested, Random Forest provided the best performance by capturing complex patterns in the dataset.

Such predictive systems can help educators identify students at risk and provide early academic support.

---

## 👩‍💻 Author

**Fathima Thahzeen**
BSc (Hons) Software Engineering Student
