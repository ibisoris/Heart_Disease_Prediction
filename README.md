# 🫀 Predicting Heart Disease Using Machine Learning

This project explores the use of machine learning techniques to predict whether a patient has heart disease based on clinical features. It demonstrates data loading, preprocessing, model training, evaluation, and feature importance visualization using Python.

## 📘 Overview

This notebook follows a complete data science workflow:

1. **Problem Definition**  
   Predict if a patient has heart disease based on their clinical data.

2. **Data Source**  
   - [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)
   - [Kaggle Dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)

3. **Evaluation Metric**  
   The goal is to achieve **≥ 95% accuracy** in predicting heart disease during the proof of concept.

4. **Approach**
   - Data exploration and visualization
   - Feature selection and preprocessing
   - Model comparison: Logistic Regression, KNN, Random Forest
   - Cross-validation and hyperparameter tuning (GridSearchCV & RandomizedSearchCV)
   - Model evaluation using accuracy, precision, recall, F1-score, ROC curves

## 📁 Files

- `heart_disease.ipynb`: Main notebook containing all code and analysis
- `heart-disease.csv`: Dataset (must be present in the same directory to run the notebook)

## 🛠️ Installation

Clone the repo and install required libraries:

```bash
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
pip install -r requirements.txt
```

Or manually install the main dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## ▶️ Usage

Start a Jupyter environment and open the notebook:

```bash
jupyter notebook
```

Run all cells in sequence to reproduce the results.

## 🔍 Features Used

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- ECG results
- Max heart rate achieved
- Exercise-induced angina
- ST depression & slope
- Number of major vessels (0–3)
- Thalassemia

## 📊 Outputs

- Heatmaps, bar plots, and histograms for EDA
- Model performance metrics
- Feature importance plots
- ROC curve and confusion matrix

## 📄 License

This project is licensed under the MIT License.

## ✍️ Author

**Your Name Ibinabo Orifama**  
[GitHub](https://github.com/ibisoris)
