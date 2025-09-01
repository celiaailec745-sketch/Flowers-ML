# Flowers-ML
Machine learning classification project using Kaggle dataset with OpenCV Logistic Regression.


This project demonstrates a simple **Machine Learning classification** task using the famous **Iris dataset**.  
We implemented a **Logistic Regression classifier** with OpenCV to distinguish between different types of iris flowers.

---

##  Project Overview
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

##  Technologies Used
- Python 3
- NumPy
- OpenCV (`cv2.ml`)
- Scikit-learn
- Matplotlib

---

##  Results
- The model is trained using **Mini-Batch Gradient Descent**.
- Achieved a good accuracy on the training and test sets.
- Example prediction:
  ```text
  Input: [5.1, 3.5, 0.4, 0.2]
  Predicted class: Setosa


##  How to Run

Clone this repository:

```bash
git clone https://github.com/celiaailec745-sketch/Flowers-ML.git
cd Flowers-ML

## Install dependencies:
pip install numpy opencv-python scikit-learn matplotlib

## Run the notebook
jupyter notebook Flowers-ML.ipynb



## Future Improvements

Extend the model to multi-class classification (Setosa, Versicolor, Virginica).

Compare Logistic Regression with other ML models (SVM, Random Forest, Neural Networks).

## References

Iris Dataset - scikit-learn

OpenCV Logistic Regression Documentation
