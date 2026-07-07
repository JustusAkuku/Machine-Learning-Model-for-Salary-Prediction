
# Project Overview
The project demonstrates how to predict salaries based on features such as education, experience, Department/Role  and performance using machine learning techniques.

# Key Sections
- Data Loading & Cleaning

- Import dataset, handle missing values, and preprocess categorical features.

- Exploratory Data Analysis (EDA)

- Visualize distributions, correlations, and feature importance.


# 📊 Dataset & Features
- The dataset (salary_dataset.csv) includes variables like:

*Education level* (e.g., Bachelor, Master, PhD)

*Years of experience*

*Department/Role*

*Performance rating*


 # 🔍 Exploratory Data Analysis (EDA)
- Average salary across the dataset: ≈ 167,500

**Salary distribution**:

- Bachelor’s degree: 158,000 – 165,000

- Master’s degree: 166,000 – 175,000

- PhD: 176,000 – 192,000

**Experience impact**:

0–5 years: ≈ 158,000

6–10 years: ≈ 167,000

11–20 years: ≈ 180,000

## 💡 Key Insights
- Education adds ~ 8,000-12,000 per level (Bachelor → Master → PhD).

- Experience contributes ~ 1,500-2,000 per year up to ~15 years, then plateaus.
  

**Department/Role matters**:

- Engineering/Tech roles average 175,000+

- HR/Admin roles average 158,000–165,000

- Performance rating can swing salaries by 10–15%

# Model Building
- 📈 Model Performance (Linear Regression)
- The model was evaluated using MAE, RMSE, and R²

# Conclusion
- The salary prediction model demonstrates robust explanatory power (R² ≈ 0.87), with average prediction errors around $4,800–$6,200. This means the model is reliable for broad salary estimation.

**Key takeaways**:

- Education consistently drives salary upward, with each level adding 8,000–12,000.

- Experience contributes about 1,500-2,000 per year until plateauing after ~15 years.

- Departmental differences are stark: Engineering averages 175,000+, while HR/Admin clusters around 158,000–165,000.

- Performance ratings can swing salaries by 10–15%, showing the importance of qualitative factors.


# How to Run
- [GitHub Repository](https://github.com/JustusAkuku/Machine-Learning-Model-for-Salary-Prediction)

- [Salary Prediction Notebook on Google Colab](https://colab.research.google.com/drive/1wxYUia2dvBpvoGPG_SPDo73BXsJtYwwO)

Run All Cells  
In Colab, click Runtime → Run all.

## DATASET

- This project uses the dataset **salary_dataset.csv**, which is included in this repository.

- You can download it directly here:  
[Download salary_dataset.csv](https://raw.githubusercontent.com/JustusAkuku/Machine-Learning-Model-for-Salary-Prediction/main/salary_dataset.csv)
