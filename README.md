# 🩺 Diabetes Prediction Using Machine Learning

## 📌 Project Overview

This project predicts whether a patient is likely to have diabetes based on medical information using Machine Learning techniques. The project includes data exploration, preprocessing, model training, evaluation, and prediction on new patient data.

The dataset used is the **Pima Indians Diabetes Dataset**, which contains various health-related attributes of patients.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Understand relationships between medical features
- Build Machine Learning models for diabetes prediction
- Compare model performance
- Predict diabetes for new patient data

---

## 📂 Dataset

**Dataset:** Pima Indians Diabetes Dataset

### Features

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

### Target

- **0** → Non-Diabetic
- **1** → Diabetic

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Dataset Overview
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Correlation Analysis
7. Data Preprocessing
8. Train-Test Split
9. Logistic Regression Model
10. Model Evaluation
11. Random Forest Model
12. Model Comparison
13. New Patient Prediction
14. Conclusion

---

## 🤖 Machine Learning Models

### Logistic Regression

- Accuracy: **77%**

### Random Forest Classifier

- Accuracy: **88%**

Random Forest outperformed Logistic Regression and was selected as the best-performing model.

---

## 📈 Results

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | 77% |
| Random Forest | 88% |

---

## 🚀 How to Run the Project

1. Clone the repository.

```bash
git clone https://github.com/Jose-shervin2007/Diabetes-Prediction-Using-Machine-Learning.git
```

2. Navigate to the project folder.

```bash
cd Diabetes-Prediction-Using-Machine-Learning
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook.

```bash
jupyter notebook
```

5. Open the notebook and run all cells.

---

## 📁 Project Structure

```
Diabetes-Prediction-Using-Machine-Learning/
│
├── Diabetes_Prediction.ipynb
├── diabetes.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📌 Future Improvements

- Hyperparameter tuning
- Feature engineering
- Cross-validation
- Deploy the model using Flask or Streamlit
- Build a web interface for diabetes prediction

---

## 👨‍💻 Author

**Jose Priyanth Shervin K**

Artificial Intelligence and Data Science Student

---

## 📄 License

This project is created for educational and internship purposes.
