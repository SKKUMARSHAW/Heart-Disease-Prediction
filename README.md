# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

Heart disease is one of the major health concerns worldwide. Early identification of potential heart disease can help healthcare professionals make better decisions and provide timely medical attention.

This project focuses on analyzing patient health data and developing Machine Learning classification models to predict the presence of heart disease based on medical attributes.

The main objective is to perform Exploratory Data Analysis (EDA), identify important health-related patterns, build predictive models, and evaluate their performance.

## 🎯 Project Objectives

- Understand and analyze patient health data.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Identify important features associated with heart disease.
- Apply statistical analysis where appropriate.
- Build and compare Machine Learning classification models.
- Evaluate models using appropriate performance metrics.
- Provide data-driven insights and recommendations for healthcare professionals.

## 📂 Dataset Description

The dataset contains patient-related medical information used to predict the presence of heart disease.

It consists of 14 columns, including:

- 1 unique patient identifier.
- 12 input features.
- 1 target variable: `heart_disease_present`.

The target variable indicates whether heart disease is present.

**Note:** The patient identifier is used for identification and is not treated as a predictive feature.

## 🛠️ Technologies & Libraries Used

| Category | Tools / Libraries |
|---|---|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Statistical Analysis | SciPy |
| Machine Learning | Scikit-learn |
| Development Environment | Jupyter Notebook |

## 🔍 Project Workflow

### 1. Data Loading
- Imported the required Python libraries.
- Loaded the training and testing datasets.
- Examined the dataset structure and dimensions.

### 2. Data Cleaning & Preprocessing
- Checked missing values.
- Identified duplicate records.
- Checked data types.
- Handled missing values where required.
- Prepared features for Machine Learning.

### 3. Exploratory Data Analysis (EDA)
- Univariate Analysis.
- Bivariate Analysis.
- Multivariate Analysis.
- Distribution analysis.
- Outlier detection.
- Correlation analysis.
- Visualization of important medical features.

### 4. Statistical Analysis
- Applied appropriate statistical techniques.
- Examined relationships between patient attributes and the target variable.
- Used hypothesis testing where appropriate.

### 5. Feature Engineering & Selection
- Identified relevant predictive features.
- Removed unnecessary identifier columns.
- Prepared the feature matrix and target variable.

### 6. Machine Learning Model Development
- Split the training data into training and validation sets.
- Applied suitable preprocessing techniques.
- Trained classification algorithms.
- Compared model performance.

### 7. Model Evaluation
Evaluated model performance using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 📊 Key Insights

The analysis aims to identify:

- Important patient health indicators associated with heart disease.
- Relationships between medical attributes and heart disease presence.
- Patterns and distributions in patient health data.
- Machine Learning models that perform well on the validation data.

## 💡 Business / Healthcare Recommendations

- Use predictive analytics as a supporting tool for early risk assessment.
- Pay attention to important health indicators identified during analysis.
- Encourage regular health checkups and preventive healthcare.
- Use data-driven insights to support healthcare planning.
- Ensure that predictions are reviewed by qualified healthcare professionals.

## 📁 Repository Structure

```text
Heart-Disease-Prediction/
│
├── PRCP-1016-HeartDiseasePred/
│   ├── Heart_Disease_Prediction.ipynb
│   ├── heart_disease_train.xlsx
│   └── heart_disease_test.xlsx
│
└── README.md
```

## ▶️ How to Run This Project

1. Clone this repository:

```bash
git clone https://github.com/SKKUMARSHAW/Heart-Disease-Prediction.git
```

2. Navigate to the project directory:

```bash
cd Heart-Disease-Prediction
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn openpyxl jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the project notebook and execute the cells.

## ⚠️ Disclaimer

This project is developed for educational and analytical purposes only. Machine Learning predictions are not a substitute for professional medical diagnosis or treatment.

## 👨‍💻 Author

**SKKUMARSHAW**

Aspiring Data Analyst | Data Science Enthusiast
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
- GitHub: [SKKUMARSHAW](https://github.com/SKKUMARSHAW)
- Email: subhamsk620@gmail.com , subhamshaw6202795590@gmail.com

---

⭐ If you find this project useful, feel free to explore the repository!
