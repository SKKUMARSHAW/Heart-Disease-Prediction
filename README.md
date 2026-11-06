# ❤️ Heart Disease Prediction Using Machine Learning

### 🩺 Predicting Heart Disease Through Data Analysis & Machine Learning

---

## 📌 Project Overview

This project focuses on analyzing patient medical data and developing a Machine Learning model to predict the presence of heart disease.

## 🎯 Project Objectives

- 🔍 Perform Exploratory Data Analysis (EDA).
- 📊 Identify patterns and relationships between medical features and heart disease.
- 🧹 Clean and preprocess the dataset.
- 🤖 Build and compare multiple classification algorithms.
- ⚙️ Perform hyperparameter tuning.
- 🏥 Provide data-driven recommendations to hospitals.

## 📂 Dataset Description

The dataset contains **180 patient records** and is provided in two separate CSV files.

| File | Description |
|---|---|
| 📄 `values.csv` | Patient medical information and input features |
| 📄 `labels.csv` | Patient identifiers and target labels |

**🎯 Target Variable:** `heart_disease_present`

- `0` – No heart disease
- `1` – Heart disease present

## 🛠️ Technologies & Libraries Used

- 🐍 Python
- 📓 Jupyter Notebook
- 🧮 Pandas, NumPy
- 📊 Matplotlib, Seaborn
- 🤖 Scikit-learn

## 🔄 Project Workflow

1. 📥 Data Loading and Integration
2. 🔎 Initial Data Understanding
3. 🧹 Data Cleaning
4. 📊 Exploratory Data Analysis
5. ⚙️ Feature Engineering and Preprocessing
6. ✂️ Train-Test Split (80:20)
7. 🤖 Model Building
8. 📈 Model Evaluation and Comparison
9. 🎯 Hyperparameter Tuning using GridSearchCV
10. 🏆 Final Model Selection
11. 🏥 Hospital Recommendations

## 🤖 Machine Learning Algorithms

Six classification algorithms were trained and compared:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree
4. Random Forest
5. Support Vector Machine (SVM)
6. Naive Bayes

## 🏆 Final Model Performance

**Selected Model: Tuned Random Forest**

| 📈 Evaluation Metric | Score |
|---|---:|
| Training Accuracy | 92.4% |
| Testing Accuracy | **91.7%** |
| Precision | 84.2% |
| Recall | **100%** |
| F1 Score | **91.4%** |

> ⭐ The model achieved 100% Recall on the test dataset of 36 patients, identifying all actual heart disease cases in that test set.

## 🔍 Key Findings

- 📌 Approximately 44.44% of patients belonged to the heart disease class.
- ❤️ Important patterns were observed in chest pain type, thal, exercise-induced angina, maximum heart rate, and ST depression.
- ⚠️ The original Random Forest showed possible overfitting.
- 🎯 Hyperparameter tuning improved the model's test performance.

## 🏥 Hospital Recommendations

- 🩺 Encourage regular cardiovascular health checkups.
- 💓 Monitor blood pressure and cholesterol levels.
- 🔎 Evaluate patients with concerning cardiac symptoms.
- 🤖 Explore ML as an additional screening support tool.
- 📢 Promote preventive healthcare awareness.

## 📁 Project Structure

```text
Heart-Disease-Prediction/
│
├── 📓 Heart_Disease_Prediction.ipynb
├── 📄 values.csv
├── 📄 labels.csv
└── 📘 README.md
```

## 🚀 How to Run the Project

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**2. Navigate to the project folder**

```bash
cd Heart-Disease-Prediction
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

**5. Open and run** `Heart_Disease_Prediction.ipynb`.

📌 Keep both CSV files in the same folder as the notebook.

## ⚠️ Limitations

- The dataset contains only 180 patient records.
- Performance may vary on new patient data.
- The model has not been clinically validated.
- Predictions should not replace professional medical diagnosis.

## 📝 Conclusion

This project demonstrates how Data Analysis, EDA, and Machine Learning can be applied to healthcare data to identify patterns associated with heart disease.

The tuned Random Forest model achieved 91.7% testing accuracy and 91.4% F1 Score on the available test dataset.

The project provided practical experience in data preprocessing, visualization, classification, model evaluation, and hyperparameter tuning.

---

### 👨‍💻 Project Information

- **Domain:** Healthcare 🏥
- **Project Type:** Machine Learning – Binary Classification 🤖
- **Environment:** Python & Jupyter Notebook 🐍

⭐ *If you find this project useful, consider giving this repository a star!*
