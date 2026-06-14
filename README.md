# Titanic Survival Prediction

## 🎯 Problem Statement
Predict whether a passenger survived the Titanic disaster based on attributes 
such as survived, pclass,	sex, age,	sibsp, parch,	fare,	embarked,	class, adult_male, deck, embark_town, alive	alone

## 📊 Dataset
- Source: Titanic Dataset (seaborn)
- Size: 891 rows, 15 columns
- Features: 'survived', 'pclass', 'sex', 'age', 'sibsp', 'parch', 'fare','embarked', 'class', 'who', 'adult_male', 'deck', 'embark_town', 'alive', 'alone'                                                                                                                                                                            
## 🛠️ Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn, Jupyter Notebook, Google Colab

## 🔍 Approach
1. Data cleaning & handling missing values (Age, Cabin, Embarked)
2. Exploratory Data Analysis (EDA) with visualizations
3. Feature encoding (Sex, Embarked) and scaling
4. Trained Logistic Regression model
5. Evaluated using accuracy, precision, recall

## 📈 Results
- Logistic Regression Accuracy: 80.44%
- Logistic Regression f1-score: 84%
- Logistic Regression recall: 87%
- Logistic Regression precision: 81%
