# Flowers-ML
Machine learning classification project using Kaggle dataset with OpenCV Logistic Regression.


This project demonstrates a simple **Machine Learning classification** task using the famous **Iris dataset**.  
We implemented a **Logistic Regression classifier** with OpenCV to distinguish between different types of iris flowers.

---

## 📌 Project Overview
- Dataset: **Iris dataset** (from `scikit-learn`)
- Features:  
  - Sepal length  
  - Sepal width  
  - Petal length  
  - Petal width  
- Task: **Binary classification** (Setosa vs Versicolor)  
  - One class (Virginica) was removed to simplify the problem.
- Algorithm: **Logistic Regression** implemented with `cv2.ml.LogisticRegression`

---

## 🛠️ Technologies Used
- Python 3
- NumPy
- OpenCV (`cv2.ml`)
- Scikit-learn
- Matplotlib

---

## 📊 Results
- The model is trained using **Mini-Batch Gradient Descent**.
- Achieved a good accuracy on the training and test sets.
- Example prediction:
  ```text
  Input: [5.1, 3.5, 0.4, 0.2]
  Predicted class: Setosa
