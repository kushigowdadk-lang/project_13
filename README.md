Here’s a clean, professional **README.md** you can directly paste into your GitHub repo 👇

---

# 🧠 Breast Cancer Detection using SVM

This project uses **Machine Learning (Support Vector Machine)** to classify breast cancer tumors as **Malignant** or **Benign** using a built-in dataset from `sklearn`.


 Project Overview

* Uses the **Breast Cancer Wisconsin Dataset**
* Applies **data preprocessing (scaling)**
* Trains a **Support Vector Machine (SVM)** model
* Evaluates performance using:

  * Accuracy Score
  * Classification Report
  * Confusion Matrix

 Technologies Used

* Python 🐍
* NumPy
* Pandas
* Scikit-learn
* Matplotlib

 Dataset Information

* Source: `sklearn.datasets.load_breast_cancer()`
* Features: 30 numerical medical attributes
* Target:

  * `0` → Malignant (Cancerous)
  * `1` → Benign (Non-cancerous)

 Workflow

1. Import required libraries
2. Load dataset
3. Convert data into DataFrame
4. Split into training & testing sets
5. Normalize data using `StandardScaler`
6. Train SVM model (`kernel = linear`)
7. Make predictions
8. Evaluate model performance
9. Visualize results using Confusion matrix

 Model Performance

The model is evaluated using:

Accuracy Score→ Overall correctness
Precision → Correct positive predictions
Recall → Ability to detect positives
F1-score** → Balance of precision & recall

 Confusion Matrix

The confusion matrix helps visualize:

* True Positives
* True Negatives
* False Positives
* False Negatives



 Example Output

* Dataset shape
* First 5 rows preview
* Model accuracy
* Classification report
* Confusion matrix visualization



 Key Learnings

* Importance of **feature scaling** in ML models
* Working with real-world datasets
* Understanding **SVM classification**
* Evaluating model performance









# project_13
project on iris flower, breast cancer, spam using logistic regression, KNN, SVM, T fit vectorize
