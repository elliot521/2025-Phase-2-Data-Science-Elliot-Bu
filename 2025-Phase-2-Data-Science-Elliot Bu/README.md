# 2025 MSA Phase 2 – Data Science Portfolio

Welcome to my Phase 2 repository for the 2025 Microsoft Student Accelerator (MSA) Data Science programme. This repository demonstrates my practical skills in exploratory data analysis, business intelligence, and deep learning model optimization through three main components.

---

## 📊 Part 1 – Exploratory Data Analysis

In Part 1, I conducted exploratory data analysis and preprocessing on a store sales dataset:

- **Data cleaning**: Removed duplicates, handled outliers, scaled numerical features, and encoded categorical variables.
- **Visualizations**: Created histograms, boxplots, and correlation heatmaps to analyze distributions and relationships.
- **Key findings**:
  - Sales distribution was skewed with negative profits in some entries.
  - Discounts had a moderate negative correlation with profit, while sales and profit showed a weak positive relationship.

🔗 [Notebook: part1-submission_ElliotBu.ipynb](./part1-submission_ElliotBu.ipynb)

---

## Bonus 📈 Part 1 – Power BI Business Intelligence Dashboard

Part 2 involved designing a Power BI dashboard to communicate business insights effectively:

- Connected and processed data to create interactive visualizations.
- Developed dashboards that highlight KPIs such as sales performance, profit by category, and regional performance breakdowns.
- Ensured the dashboard is clear, interactive, and decision-oriented.

🔗 [Power BI File: Phase2_PowerBi_ElliotBu.pbix](./Phase2_PowerBi_ElliotBu.pbix)

---

## 🤖 Part 2 – Machine Learning Model Development

In Part 2, I focused on building and evaluating machine learning models to derive predictive insights from the dataset:

- **Data preprocessing**:
  - Cleaned and prepared data by handling missing values, encoding categorical features, and scaling numerical variables.
- **Model training and evaluation**:
  - Trained multiple models, including Random Forests and Gradient Boosting Machines.
  - Evaluated model performance using metrics such as accuracy, precision, recall, and F1-score.
- **Feature importance analysis**:
  - Identified key drivers of the target variable to inform business decisions.
- **Key outcomes**:
  - Developed an optimized predictive model with strong generalization performance.
  - Provided interpretations of model outputs to support practical deployment.

🔗 [Notebook: part2_submission_ElliotBu.ipynb](./part2_submission_ElliotBu.ipynb)

---

## 🤖 Part 3 – Knowledge Distillation for Image Classification

In Part 3, I implemented **knowledge distillation** to compress deep learning models while maintaining accuracy:

- **Project title**: Improving Image Classification with Knowledge Distillation: A Student-Teacher Approach
- **Goal**: Train a smaller ResNet18 student model to mimic a ResNet34 teacher on the CIFAR-100 dataset.
- **Approach**:
  - Used Kullback-Leibler Divergence and cross-entropy loss with temperature scaling for distillation.
  - Trained both models and evaluated validation accuracy.
- **Results**:
  - Teacher (ResNet34): 94.85% accuracy, 21.8M parameters.
  - Student with KD (ResNet18): 85.76% accuracy, 11.2M parameters.
- **Impact**: Demonstrated significant model compression with minimal performance loss, suitable for edge deployment.

🔗 [Notebook: part3-submission_ElliotBu.ipynb](./part3-submission_ElliotBu.ipynb)  
📄 [IEEE Report: Improving Image Classification with Knowledge Distillation](./IEEE%20Report%20Elliot%20Bu.pdf)

---

## 📁 Repository Structure

```
Part1/
└── part1-submission_ElliotBu.ipynb
Part2/
└── part2_submission_ElliotBu.ipynb
Part3/
└── part3-submission_ElliotBu.ipynb
└── IEEE Report Elliot Bu.pdf
submission.csv
README.md
```

---

## ✨ Summary

This repository consolidates my data science skills in:

1. **Data wrangling and EDA**
2. **Machine Learning Model Development**
3. **Deep learning model compression for real-world deployment**
   
---

*Prepared by Elliot Bu, University of Auckland, July 2025.*
