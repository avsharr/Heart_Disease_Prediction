Heart Disease Prediction using Machine Learning

This project uses various machine learning models to predict the presence of heart disease based on patient data. It includes class balancing with SMOTE, model training, evaluation, and comparison of different algorithms.


## 📁 Dataset

- **Name**: `heart-disease.csv`
- **Target column**: `target` (1 = Disease, 0 = Healthy)
- **Source**: [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)


📊 Workflow

1. Data loading and EDA
2. Class distribution analysis
3. Balancing classes with SMOTE
4. Model training:
    - Logistic Regression
    - K-Nearest Neighbors
    - Random Forest
5. Evaluation:
    - Accuracy
    - Confusion Matrix
    - ROC Curve
    - Precision-Recall Curve
6. Final classification report


📈 Results

- Models were evaluated on accuracy and interpretability.
- The best-performing model is automatically selected and reported.


🧰 Libraries Used
bash
pandas
numpy
seaborn
matplotlib
scikit-learn
imbalanced-learn
