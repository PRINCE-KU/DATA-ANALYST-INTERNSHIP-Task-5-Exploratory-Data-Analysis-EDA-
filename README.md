# DATA-ANALYST-INTERNSHIP-Task-5-Exploratory-Data-Analysis-EDA-
# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Task 5 - Data Analyst Internship Project

This project is part of my Data Analyst Internship where I performed **Exploratory Data Analysis (EDA)** on the famous Titanic dataset to identify patterns, trends, and correlations that influenced passenger survival.

---

## 📊 Objective

- Perform EDA using **Python (Pandas, Matplotlib, Seaborn)**
- Extract insights using visual and statistical exploration
- Identify key features influencing survival
- Summarize findings with graphs and observations

---

## 📁 Dataset

- **Name:** Titanic Dataset  
- **Source:** [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)
- **Direct Access via Code:**  
  ```python
  url = "https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"
  df = pd.read_csv(url)

🛠 Tools Used
Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook

🔍 EDA Steps Covered
Import Libraries & Load Dataset

Dataset Overview (.head(), .info(), .describe())

Missing Values Handling

Univariate Analysis (histograms, boxplots, countplots)

Bivariate Analysis (e.g., survival vs gender/class)

Multivariate Analysis (correlation heatmap, pairplot)

Summary of Insights

📈 Key Observations
Women had a higher survival rate than men.

1st class passengers had better survival chances.

Children (younger age) were more likely to survive.

Fare and Pclass were strongly correlated with survival.

### 🔍 Key Insights:

- Females had a higher chance of survival than males.
- Passengers in 1st class survived more compared to those in 2nd or 3rd class.
- Children and young passengers were more likely to survive.
- Higher fare-paying passengers had better survival chances.
- Strong correlation found between Fare, Pclass, and Survived.

  ✅ Short Interview Q&A – EDA
1. What is EDA?
EDA (Exploratory Data Analysis) is used to understand data using stats and visuals. It helps find patterns, missing values, and outliers.

2. Plots to check correlation?

Heatmap

Pairplot

Scatter plot

3. How to handle skewed data?
Use:

Log transformation

Square root or Box-Cox

Remove outliers

4. How to detect multicollinearity?

Check correlation matrix

Use VIF (Variance Inflation Factor)

5. What are univariate, bivariate, multivariate?

Univariate: One variable (e.g., Age)

Bivariate: Two variables (e.g., Age vs Survived)

Multivariate: More than two (e.g., Age, Fare, Pclass vs Survived)

6. Heatmap vs Pairplot?

Heatmap: Shows numeric correlations

Pairplot: Visualizes relationships with plots

7. How to summarize insights?

Use bullet points

Highlight key trends (e.g., females survived more, 1st class had higher survival)



  
