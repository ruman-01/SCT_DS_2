# Titanic Dataset: Data Cleaning and EDA 🚢

This repository contains the code and findings for Task 02 of my Data Science Internship at SkillCraft Technology. The objective of this project is to perform data cleaning and exploratory data analysis (EDA) on the famous Titanic dataset from Kaggle to uncover the factors that influenced passenger survival.

## 🎯 Objective
* **Data Cleaning:** Identify and handle missing values, outliers, and categorical variables to prepare the dataset for analysis.
* **Exploratory Data Analysis (EDA):** Analyze the relationships between variables (like age, gender, passenger class) and survival rates using statistical summaries and data visualization.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## 🧹 Data Cleaning Process
1. **Handling Missing Values:** * `Age`: Imputed missing values using the median to avoid skewing the distribution.
   * `Embarked`: Imputed the few missing values with the mode ('S').
   * `Cabin`: Dropped the feature entirely as over 75% of the data was missing.
2. **Data Transformation:** Formatted appropriate data types for visualization.

## 📊 Key Insights (EDA)
Based on the visualizations and statistical analysis, the following patterns were identified:
1. **Gender:** Survival rates were heavily influenced by gender. Females had a dramatically higher survival rate (~74%) compared to males (~19%).
2. **Socio-Economic Status:** Passenger class (`Pclass`) played a major role. First-class passengers had a much higher probability of survival (~63%) than those in third class (~24%).
3. **Age:** The age distribution shows that young children had a noticeably higher chance of survival compared to other age groups.

## 📂 Repository Structure
* `train.csv`: The training dataset used for the analysis.
* `test.csv`: The testing dataset.
* `gender_submission.csv`: Sample submission file.
* `Titanic_EDA.ipynb`: The Jupyter Notebook containing the complete Python code for cleaning and visualization.

## 🚀 How to Run
1. Clone the repository: `git clone <your-repository-url>`
2. Ensure you have the required libraries installed (`pip install pandas matplotlib seaborn`).
3. Open `Titanic_EDA.ipynb` in Jupyter Notebook or Google Colab and run the cells sequentially.
