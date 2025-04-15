ELEVATE_LABS-Task-5
Exploratory Data Analysis on Titanic dataset (EDA)

Titanic Banner

📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries such as Pandas, Seaborn, and Matplotlib. The goal is to uncover trends, detect anomalies, and extract meaningful insights from the data.

🧠 Objective
Clean and preprocess the Titanic dataset
Perform univariate, bivariate, and multivariate analysis
Visualize relationships between features (like Age, Gender, Pclass, Fare, Survival)
Summarize insights and patterns using visual storytelling
🧰 Tools & Technologies Used
Tool	Purpose
Python	Data analysis & processing
Pandas	Data manipulation
Matplotlib	Visualization
Seaborn	Advanced plotting
Jupyter Notebook	Coding & documentation

📊 Key Findings (Summary)
👩‍🦰 Gender: Females had a significantly higher survival rate.
🏷️ Class: First-class passengers had the highest survival chance.
👶 Age: Children had relatively higher survival rates than adults.
💸 Fare: Passengers who paid higher fares tended to survive more.
🌍 Embarked Port: Passengers from Cherbourg had higher survival.
📈 Sample Visualizations
   

All charts are included in the notebook and PDF report

🧪 Process Followed
Data Cleaning – Handled missing values in Age, Fare, and removed Cabin.
Univariate Analysis – Explored individual features (Age, Sex, Fare, etc.)
Bivariate Analysis – Visualized survival by Sex, Pclass, Age.
Multivariate Analysis – Used heatmaps and pairplots to explore relationships.
Observations – Documented insights from each visualization.
🧩 Interview Questions & Answers
1️⃣ What is EDA and why is it important?
EDA (Exploratory Data Analysis) is the process of analyzing datasets to summarize their main characteristics using statistics and visualization. It helps in discovering patterns, spotting anomalies, testing hypotheses, and choosing the right model or preprocessing technique.

2️⃣ Which plots do you use to check correlation?
heatmap (shows correlation matrix)
pairplot (scatter plots for variable pairs)
scatterplot (for two numerical variables)
3️⃣ How do you handle skewed data?
Log transformation
Square root transformation
Box-Cox transformation
Use of robust scaling or binning
4️⃣ How to detect multicollinearity?
Correlation matrix (high correlation between independent variables)
Variance Inflation Factor (VIF)
5️⃣ What are univariate, bivariate, and multivariate analyses?
Univariate: Analysis of a single variable (e.g., histogram of Age)
Bivariate: Analysis of two variables (e.g., survival by gender)
Multivariate: Analysis of three or more variables (e.g., heatmap or pairplot)
6️⃣ Difference between heatmap and pairplot?
Heatmap: Shows correlations as a matrix using color gradients
Pairplot: Visualizes scatter plots and distributions between every pair of variables
7️⃣ How do you summarize your insights?
By combining visual observations and statistical summaries to highlight:

Key trends
Correlations
Anomalies
Possible feature importance
