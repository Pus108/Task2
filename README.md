 🧼 Task 02: Data Cleaning & Exploratory Data Analysis (EDA)
 📌 Objective

This project focuses on **data cleaning** and **exploratory data analysis (EDA)** using a dataset of choice — such as the **Titanic dataset** from Kaggle. The goal is to understand the structure of the data, identify missing or inconsistent values, and uncover meaningful **patterns**, **trends**, and **relationships** between variables.
📂 Dataset

Source: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
Description: The dataset provides information about passengers on the Titanic, including:
  - PassengerId
  - Name, Age, Sex
  - Ticket, Fare
  - Cabin, Embarked
  - Pclass (Ticket class)
  - SibSp (Number of siblings/spouses aboard)
  - Parch (Number of parents/children aboard)
  - Survived (Target variable)

 🛠️ Technologies Used

- Python
-  Google Colab
- Libraries:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
🔍 EDA Process
1. Data Cleaning
- Handled missing values in `Age`, `Cabin`, and `Embarked`
- Dropped unnecessary columns like `Ticket` and `Cabin`
- Converted categorical columns to numeric using label encoding or one-hot encoding
 2. Univariate Analysis
- Plotted distributions of `Age`, `Fare`, and `Pclass`
- Analyzed survival rates across `Sex` and `Pclass`
 3. Bivariate/Multivariate Analysis
- Correlation matrix and heatmap
- Survival rates by combinations of `Sex`, `Pclass`, and `Embarked`
- Visualized relationships using bar plots, box plots, and scatter plots

📊 Key Insights
- Female passengers had a much higher survival rate than males.
- Younger passengers and those in 1st class were more likely to survive.
- Passengers who embarked from Cherbourg (C) had a higher chance of survival.
- High correlation observed between `Pclass` and survival.
