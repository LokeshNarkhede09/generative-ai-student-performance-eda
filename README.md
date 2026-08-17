# Impact of Generative AI on Student Academic Performance

## 📌 Project Overview

This project uses Exploratory Data Analysis (EDA) to study how Generative AI usage is related to students' academic performance, study habits, skill retention, anxiety, and burnout.

The analysis explores whether factors such as AI usage hours, tool diversity, and AI dependency have a meaningful relationship with students' academic outcomes.

## 🎯 Objectives

- Analyze Generative AI usage patterns among students.
- Examine the relationship between Generative AI usage and GPA.
- Study the effect of AI usage on study habits and learning behavior.
- Analyze skill retention and AI dependency.
- Explore student anxiety and burnout levels.

## 📊 Dataset

- **Total Records:** 30,900 students
- **Total Columns:** 16
- **Categorical Columns:** 9
- **Numerical Columns:** 7

The dataset contains information about students' academic performance, Generative AI usage, study habits, AI dependency, anxiety, skill retention, and burnout.

## 🧹 Data Cleaning

The following data cleaning steps were performed:

- Handled missing values using **mode** for categorical columns and **median** for numerical columns.
- Removed **123 duplicate records** using `drop_duplicates()`.
- Converted mixed data types into appropriate numeric formats.
- Final dataset after duplicate removal: **30,777 records**.

## 📈 EDA Performed

### Univariate Analysis
- Weekly GenAI Hours
- Post-Semester GPA
- Anxiety Level During Exams
- Burnout Risk Level

### Bivariate Analysis
- Weekly GenAI Hours vs Post-Semester GPA
- Weekly GenAI Hours vs Traditional Study Hours
- Major Category vs Post-Semester GPA
- Paid Subscription vs GenAI Hours
- Major Category vs Burnout Risk Level

### Multivariate Analysis
- Correlation analysis using a heatmap

## 🔍 Key Findings

- There is almost **no linear relationship** between Weekly GenAI Hours and Post-Semester GPA.
- Correlation between **Weekly GenAI Hours and GPA = -0.01**.
- Correlation between **Tool Diversity and GPA = 0.02**.
- More than **14,000 students** fall under the Medium Burnout category.
- Students with paid AI subscriptions tend to use Generative AI for more hours.
- Average GPA remains relatively similar across different academic majors.
- Study habits and consistency may have a greater influence on academic performance than AI usage alone.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📁 Project Files

- `Generative_AI_Student_Performance_EDA.ipynb` — Complete EDA notebook
- `AI_Impact_on_Student_Performance.csv` — Dataset used for analysis
- `EDA_Project_Presentation.pptx` — Project presentation
- `README.md` — Project documentation

## 👨‍💻 Author

**Lokesh Narkhede**

**Project:** Exploratory Data Analysis (EDA)

**Domain:** Generative AI & Student Academic Performance

