# Student-Campus-Placement-Predictions
- enrgvijeriae
**Author:** D Gokul Kanna  

---

## Project Overview
This project focuses on **predicting campus placement outcomes for university students** using machine learning. By analyzing historical academic and professional data, this system enables **data-driven decision-making** for universities, recruiters, and students alike.  

Accurate predictions can:  
- Help career services identify high-risk students and provide targeted support.  
- Allow recruiters to focus efforts efficiently.  
- Assist students in understanding factors impacting their employability.

---

## Dataset
- **Source:** Primary data collected from 986 students (2019–2020)  
- **Scope:** Students who graduated within the standard time frame  
- **Features:**  
  - Stream: Arts, Commerce, Professional, Science  
  - Current Degree: BVC, BVOC, BSW, BSC, BCOM, BCA, BBA, BA  
  - Backlogs: Presence of backlog across 6 semesters  
  - Work Experience: Any prior internships or work  
  - Placement Status: Placed via campus recruitment or not  
  - Academic Scores: 10th, 12th, and UG percentages  

---

## Objective
- Predict the **likelihood of student placement** based on academic and experiential factors.  
- Evaluate multiple machine learning algorithms to determine the **most effective model**.  
- Provide actionable insights for stakeholders to **improve student outcomes**.  

---

## Evaluation Metrics
- **Accuracy:** For balanced datasets  
- **Precision, Recall, F1 Score:** Critical for imbalanced scenarios  
- **Confusion Matrix:** For detailed analysis of True/False Positives and Negatives  

---

## Algorithms Used

| Algorithm | Key Concept | Advantages | Limitations | Accuracy |
|-----------|------------|------------|-------------|---------|
| **KNN** | Classification based on nearest neighbors | Simple, interpretable | Slower with high-dimensional data | 73.73% |
| **Naïve Bayes** | Probabilistic classifier using Bayes’ theorem | Fast, works well with small data | Assumes feature independence | 81.81% |
| **Random Forest** | Ensemble of decision trees | Handles many features, reduces overfitting | Computation heavy | 86.86% |
| **Logistic Regression** | Predicts probability of binary outcome | Interpretable, efficient | Assumes independence, sensitive to outliers | 89.89% |
| **SVM** | Finds optimal hyperplane to separate classes | High-dimensional data handling, robust | Requires parameter tuning | 90.40% |

---

## Results
- **SVM** achieved the **highest accuracy (90.40%)**, making it the most reliable for predicting placements.  
- Logistic Regression (89.89%) and Random Forest (86.86%) also performed strongly.  
- KNN (73.73%) and Naïve Bayes (81.81%) provided baseline comparisons.  

---

## Business Implications
- Universities can proactively **identify students at risk of not getting placed** and offer support programs.  
- Recruiters can **prioritize candidates likely to succeed**, saving time and resources.  
- Students gain **data-backed insights** into factors influencing employability, enabling informed decisions on skills development or internships.  

---

## Tools & Environment
- **Programming Language:** Python  
- **Libraries:** scikit-learn, pandas, numpy, matplotlib, seaborn  
- **Environment:** Jupyter Notebook / Python IDE  

---

## How to Use
1. Load the dataset into Python.  
2. Preprocess data (handle missing values, encode categorical variables).  
3. Train multiple classifiers: KNN, Naïve Bayes, Random Forest, Logistic Regression, SVM.  
4. Evaluate models using **accuracy, precision, recall, F1-score, and confusion matrix**.  
5. Compare results and select the most effective model for deployment or analysis.  

---

> **Note:** Placement prediction is a strategic decision-making tool; accurate predictions help **universities, recruiters, and students make smarter career choices**.  
