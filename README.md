# Titanic-Dataset-Survival-Rate-Machine-Learning

# 🚢 Titanic Survival Prediction — Machine Learning

A hands-on Machine Learning project exploring the factors associated with passenger survival on the Titanic dataset.

---

## 🎯 Project Overview

The Titanic dataset is a classic benchmark for learning Data Science and Machine Learning. In this project, passenger information is analyzed to uncover key survival trends, followed by building a classification model to predict whether a passenger survived or did not survive.

### 🔎 Key Questions Explored
* 👥 **Gender:** How does gender relate to survival rates?
* 🎫 **Passenger Class:** How does socioeconomic status (`Pclass`) impact survival?
* 💰 **Fare:** Does the ticket fare provide useful predictive information?
* 🎂 **Missing Data:** How should missing age values be handled effectively?
* 🤖 **Machine Learning:** Can a model accurately predict passenger survival based on these features?

---

## 🛠️ Tools & Technologies

| Category | Tool / Library | Purpose |
| :--- | :--- | :--- |
| **Programming Language** | 🐍 Python | Core logic and scripting |
| **Data Manipulation** | 🐼 Pandas, 🔢 NumPy | Data cleaning, manipulation, and numerical operations |
| **Visualization** | 📊 Matplotlib, 📈 Seaborn | Exploratory data analysis and visual insights |
| **Machine Learning** | 🤖 Scikit-learn | Model training, splitting, and evaluation |
| **Environment** | 📓 Jupyter Notebook | Experimentation and documentation |
| **Version Control** | 🌱 Git & GitHub | Tracking changes and collaboration |

---

## 🔄 Project Workflow

```text
📂 Titanic Dataset
       ↓
🔍 Data Exploration (EDA)
       ↓
🧹 Data Preprocessing & Cleaning
       ↓
🎯 Feature Selection
       ↓
✂️ Train / Test Split
       ↓
🤖 Model Training (Logistic Regression)
       ↓
🔮 Prediction
       ↓
📊 Model Evaluation
```
---

## 📊 Machine Learning Approach
1. Features & Target
Features (X):

Pclass (Passenger class)

Sex (Passenger gender — converted via one-hot encoding)

Age (Passenger age — missing values filled with the median)

Fare (Passenger fare)

Target (y):

Survived (0 = Did not survive, 1 = Survived)

## 📈 Evaluation & Results
Baseline Model: Logistic Regression

Metric: Accuracy Score

Further evaluation metrics (such as Precision, Recall, and ROC-AUC) will be integrated as the project expands.

📓 Notebook
The complete exploration, preprocessing, training, prediction, and analysis workflow can be found in the accompanying Jupyter Notebook: [titanic.ipynb](./titanic.ipynb)

🚀 Getting Started
Clone the repository:
git clone https://github.com/vickyrocks-torvaldshugefan/Titanic-Dataset-Survival-Rate-Machine-Learning.git
cd Titanic-Dataset-Survival-Rate-Machine-Learning

## Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

