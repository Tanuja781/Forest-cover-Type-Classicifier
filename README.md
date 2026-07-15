# 🌲 Forest Cover Type Classifier

## 📌 Project Overview

The Forest Cover Type Classifier is a Machine Learning project developed to predict the type of forest cover based on cartographic and environmental features. The project uses supervised machine learning algorithms to classify forest cover into multiple categories using the UCI Forest CoverType dataset.

The project involves data preprocessing, exploratory data analysis, model training, evaluation, hyperparameter optimization, and deployment preparation.

---

## 🎯 Objectives

- Predict forest cover types using cartographic features.
- Compare the performance of different machine learning models.
- Optimize the selected model for improved accuracy.
- Analyze feature importance to understand influential variables.
- Prepare the model for deployment using Streamlit.

---

## 📂 Dataset

Dataset: UCI Forest CoverType Dataset

The dataset contains cartographic variables such as:

- Elevation
- Aspect
- Slope
- Horizontal Distance to Hydrology
- Vertical Distance to Hydrology
- Horizontal Distance to Roadways
- Hillshade (9 AM, Noon, 3 PM)
- Horizontal Distance to Fire Points
- Wilderness Areas
- Soil Types

Target Variable

- Cover_Type

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Streamlit

---

## 📊 Project Workflow

### 1. Data Collection

- Load the UCI Forest CoverType dataset.
- Verify dataset integrity.

---

### 2. Data Exploration

- Dataset information
- Missing value analysis
- Duplicate value analysis
- Statistical summary
- Feature distribution
- Target class distribution

---

### 3. Exploratory Data Analysis

- Histograms
- Scatter plots
- Correlation analysis
- Feature relationship analysis

---

### 4. Data Preprocessing

- Feature selection
- Target separation
- Train-Test Split

---

### 5. Machine Learning Models

#### Random Forest Classifier

- Model training
- Prediction
- Performance evaluation

#### Gradient Boosting Classifier

- Model training
- Prediction
- Performance comparison

---

### 6. Model Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

---

### 7. Model Optimization

- Cross Validation
- GridSearchCV
- Hyperparameter Tuning

---

### 8. Feature Importance

- Feature ranking
- Visualization
- Interpretation

---

### 9. Model Serialization

- Save trained model using Joblib
- Load saved model
- Prediction testing

---

### 10. Deployment

- Streamlit Web Application
- User-friendly prediction interface

---

## 📁 Project Structure

```
Forest-Cover-Type-Classifier/
│
├── covtype.csv
├── Forest_Cover_Type_Classifier.ipynb
├── forest_cover_classifier.pkl
├── app.py
├── requirements.txt
├── README.md
└── images/
```

---

## 📈 Machine Learning Algorithms

- Random Forest Classifier
- Gradient Boosting Classifier

---

## 📌 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Cross Validation Score

---

## 🚀 Future Improvements

- Hyperparameter optimization using RandomizedSearchCV
- Model deployment on cloud platforms
- Real-time prediction interface
- Interactive visualizations
- Feature engineering for improved accuracy

---

## 👩‍💻 Author

Tanuja Dhanraj Patil

Machine Learning Intern

