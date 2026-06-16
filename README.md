# 🚢 Titanic Survival Prediction

A Machine Learning project that predicts whether a passenger survived the Titanic disaster based on demographic and travel-related features such as age, gender, passenger class, fare, and family information.

## 📌 Project Overview

The Titanic Survival Prediction project is a binary classification problem. The objective is to build a machine learning model that can accurately predict whether a passenger survived (`1`) or did not survive (`0`) using historical Titanic passenger data.

This project demonstrates the complete machine learning workflow including:

- Data Loading
- Data Preprocessing
- Handling Missing Values
- Feature Encoding
- Exploratory Data Analysis (EDA)
- Model Training
- Model Evaluation
- Prediction on New Data

---

## 📊 Dataset

The dataset contains information about Titanic passengers, including:

- Passenger Class (Pclass)
- Name
- Gender (Sex)
- Age
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Ticket Number
- Fare
- Cabin
- Embarked Port
- Survival Status

Dataset Source:
https://www.kaggle.com/datasets/yasserh/titanic-dataset

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🤖 Machine Learning Models

The following classification algorithms can be used and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (Optional)

---

## 📂 Project Structure

```text
Titanic_Survival_Prediction/
│
├── Titanic_Survival_Prediction.ipynb
├── Titanic-Dataset.csv
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/ishitapatel14/Titanic_Survival_Prediction.git
```

Move into the project directory:

```bash
cd Titanic_Survival_Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Titanic_Survival_Prediction.ipynb
```

Run all cells to train the model and generate predictions.

---

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

Typical model accuracy ranges between **80% and 85%** depending on preprocessing and algorithm selection.

---

## 📋 Features Used for Prediction

- Passenger Class (Pclass)
- Gender (Sex)
- Age
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Fare
- Embarked Port

---

## 🔮 Sample Prediction

The trained model can predict whether a passenger would have survived based on the provided input features.

Example Output:

```text
Prediction: Survived
```

or

```text
Prediction: Did Not Survive
```

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Feature Engineering
- XGBoost Implementation
- Model Deployment using Flask or Streamlit
- Interactive Dashboard

---

## 📚 Learning Outcomes

Through this project, the following concepts were practiced:

- Data Cleaning
- Feature Engineering
- Classification Algorithms
- Model Evaluation
- Machine Learning Workflow
- Python for Data Science

---

## 👩‍💻 Author

**MANAN SUTARIYA**


---

## ⭐ If you found this project useful, consider giving it a star!
