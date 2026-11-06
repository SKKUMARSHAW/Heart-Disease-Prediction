# Heart Disease Prediction Using Machine Learning

## Project Overview

This project focuses on analyzing patient medical data and developing a Machine Learning model to predict the presence of heart disease.

The project uses patient health information such as age, blood pressure, cholesterol, chest pain type, maximum heart rate, and exercise-induced angina to identify patterns associated with heart disease.

The main objective is to use Data Analysis and Machine Learning techniques to support early heart disease risk identification.

## Project Objectives

- Perform Exploratory Data Analysis (EDA) to understand patient health information.
- Identify patterns and relationships between medical features and heart disease.
- Clean and preprocess the dataset for machine learning.
- Build and compare multiple classification algorithms.
- Perform hyperparameter tuning to improve model performance.
- Provide recommendations to hospitals based on the analysis.

## Dataset Description

The dataset contains 180 patient records and is provided in two separate CSV files.

**Dataset Files:**

- `values.csv` – Contains patient medical information and input features.
- `labels.csv` – Contains patient identifiers and corresponding target labels.

**Target Variable:** `heart_disease_present`

- `0` – No heart disease
- `1` – Heart disease present

The two datasets are combined using the common `patient_id` column.

## Technologies & Libraries Used

- **Programming Language:** Python
- **Development Environment:** Jupyter Notebook
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn

## Project Workflow

1. Data Loading and Integration
2. Initial Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering and Preprocessing
6. Train-Test Split (80:20)
7. Model Building
8. Model Evaluation and Comparison
9. Hyperparameter Tuning using GridSearchCV
10. Final Model Selection
11. Hospital Recommendations

## Machine Learning Algorithms

Six classification algorithms were trained and compared:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree
4. Random Forest
5. Support Vector Machine (SVM)
6. Naive Bayes

Random Forest was selected for further hyperparameter tuning using GridSearchCV with 5-fold cross-validation.

## Final Model Performance

The tuned Random Forest model achieved the following results on the test dataset:

| Evaluation Metric | Score |
|---|---:|
| Training Accuracy | 92.4% |
| Testing Accuracy | 91.7% |
| Precision | 84.2% |
| Recall | 100% |
| F1 Score | 91.4% |

The model achieved 100% Recall on the test dataset, meaning it identified all actual heart disease cases among the 36 test records.

## Key Findings

- The dataset contained 180 patient records with no missing values.
- Approximately 44.44% of the patients belonged to the heart disease class.
- Important patterns were observed in chest pain type, thal, exercise-induced angina, maximum heart rate, and ST depression.
- The original Random Forest showed possible overfitting.
- Hyperparameter tuning reduced the training accuracy gap and improved test performance.

## Hospital Recommendations

Based on the data analysis and model results:

- Encourage regular cardiovascular health checkups.
- Monitor important health indicators such as blood pressure and cholesterol.
- Provide appropriate clinical evaluation for patients with concerning cardiac symptoms.
- Use machine learning as an additional screening support tool for identifying potentially high-risk patients.
- Promote preventive healthcare and awareness programs.

## Project Structure

```text
Heart-Disease-Prediction/
│
├── Heart_Disease_Prediction.ipynb
├── values.csv
├── labels.csv
└── README.md
```

## How to Run the Project

1. Clone this repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Navigate to the project folder:

```bash
cd Heart-Disease-Prediction
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Heart_Disease_Prediction.ipynb` and run the cells in order.

**Note:** Keep both CSV files in the same folder as the notebook so the dataset loading code works correctly.

## Limitations

- The dataset contains only 180 patient records.
- Model performance may vary on new patient data.
- The model has not been clinically validated.
- Predictions should not replace professional medical diagnosis.

## Conclusion

This project demonstrates how Data Analysis, Exploratory Data Analysis, and Machine Learning can be applied to healthcare data to identify patterns associated with heart disease.

The tuned Random Forest model achieved 91.7% testing accuracy and 91.4% F1 Score on the available test dataset. The project provides practical experience in data preprocessing, visualization, classification, model evaluation, and hyperparameter tuning.

**Domain:** Healthcare

**Project Type:** Machine Learning – Binary Classification
