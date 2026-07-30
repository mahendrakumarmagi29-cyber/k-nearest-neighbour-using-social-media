# 📱 Social Media Addiction Level Prediction using K-Nearest Neighbors (KNN)

## 📌 Project Overview

This project predicts the **Addiction Level** of social media users using the **K-Nearest Neighbors (KNN)** classification algorithm. The model analyzes user behavior, lifestyle, and psychological factors to classify users into different addiction levels.

The project demonstrates a complete machine learning workflow, including data preprocessing, feature engineering, model building, and performance evaluation.

---

# 🎯 Problem Statement

Excessive social media usage has become a significant concern, affecting mental health, sleep quality, productivity, and overall well-being. Identifying users at risk of social media addiction can help support early intervention and awareness.

This project develops a KNN classification model to predict users' addiction levels based on demographic, behavioral, and psychological features.

---

# 🎯 Objectives

* Analyze the social media addiction dataset.
* Perform data cleaning and preprocessing.
* Replace zero values using the median.
* Handle missing values and duplicate records.
* Encode categorical features using Label Encoding.
* Balance the dataset using SMOTE.
* Standardize features using StandardScaler.
* Build a K-Nearest Neighbors (KNN) classification model.
* Evaluate the model using standard classification metrics.

---

# 📊 Dataset

The dataset contains user information such as:

* Age
* Gender
* Daily Usage Hours
* Sleep Hours
* Anxiety Score
* Depression Score
* Self Esteem
* Productivity Loss
* Relationship Status
* Other behavioral attributes

**Target Variable**

* Addiction_Level

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Matplotlib
* Seaborn
* Jupyter Notebook / VS Code

---

# 🔄 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Handle Missing Values
5. Remove Duplicate Records
6. Replace Zero Values with Median
7. Label Encode Categorical Columns
8. Split Features and Target
9. Train-Test Split
10. Balance Training Data using SMOTE
11. Standardize Features using StandardScaler
12. Train K-Nearest Neighbors (KNN) Model
13. Predict Test Data
14. Evaluate Model Performance

---

# 📈 Exploratory Data Analysis

The following visualizations were created:

* Count Plot
* Histogram
* Box Plot
* Violin Plot
* Scatter Plot
* Pair Plot
* Correlation Heatmap
* Distribution Plot

---

# 🤖 Machine Learning Model

**Algorithm**

* K-Nearest Neighbors (KNN)

**Hyperparameters**

* n_neighbors = 5 (or tuned value)
* Distance Metric = Euclidean / Manhattan
* Feature Scaling = StandardScaler
* Data Balancing = SMOTE

---

# 📊 Evaluation Metrics

The model is evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score
* Classification Report

---

# 📁 Project Structure

```text
Social-Media-Addiction-KNN/
│
├── dataset/
│   └── knn_dataset.csv
│
├── notebook/
│   └── KNN_Model.ipynb
│
├── images/
│   ├── heatmap.png
│   ├── histogram.png
│   ├── boxplot.png
│   └── confusion_matrix.png
│
├── README.md
└── requirements.txt
```

---

# 🚀 How to Run

1. Clone the repository.
2. Install the required libraries.
3. Open the notebook or Python script.
4. Run all cells in sequence.
5. View the evaluation metrics and predictions.

---

# 📌 Results

* Successfully preprocessed the dataset.
* Balanced the training data using SMOTE.
* Standardized features with StandardScaler.
* Built and evaluated a KNN classification model.
* Predicted social media addiction levels using user behavior and psychological factors.

---

# 🔮 Future Enhancements

* Hyperparameter tuning using GridSearchCV.
* Compare KNN with Random Forest, Decision Tree, Logistic Regression, SVM, and XGBoost.
* Deploy the model as a web application using Flask or Streamlit.
* Integrate real-time prediction and visualization dashboards.

---

# 👨‍💻 Author

**Mahendrakumar**

B.Tech Information Technology

Aspiring Data Scientist | Machine Learning Enthusiast

Python | SQL | Power BI | Machine Learning | Data Analytics
