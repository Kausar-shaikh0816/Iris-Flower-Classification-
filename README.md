Iris Flower Classification using Machine Learning

This project demonstrates a complete Machine Learning pipeline to classify iris flowers into three species using Logistic Regression.

Project Overview

The goal of this project is to classify iris flowers into:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

based on four input features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---
 Machine Learning Workflow

1. Data Loading
2. Data Preprocessing
   - Feature & Label Separation
   - Label Encoding
   - Train-Test Split
3. Feature Scaling using StandardScaler
4. Model Training using Logistic Regression
5. Model Evaluation
   - Accuracy Score
   - Confusion Matrix
6. Prediction on New Data

---

 Model Used

Logistic Regression

Why Logistic Regression?
- Works well for multi-class classification
- Efficient for small datasets
- Provides high accuracy on Iris dataset

---

 Model Performance

- Training Accuracy: 96.6%
- Test Accuracy: ~100%
- Confusion Matrix shows perfect class separation

---

 Example Predictions

| Input (SepalLength, SepalWidth, PetalLength, PetalWidth) | Prediction |
|----------------------------------------------------------|------------|
| 5.1, 3.5, 1.4, 0.2 | Iris-setosa |
| 6.5, 3.0, 5.2, 2.0 | Iris-virginica |

---

## 📂 Project Structure
