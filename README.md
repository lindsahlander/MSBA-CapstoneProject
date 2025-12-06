# Home Credit Default Risk Project

## Business Problem
Many individuals—particularly those who are unbanked or underbanked—struggle to access loans due to a lack of formal credit history. Without credit, they are often unable to build financial stability or acquire property, reinforcing cycles of financial exclusion.

Home Credit aims to serve these underserved populations by providing accessible credit solutions. To do this sustainably, they must accurately predict the risk of loan defaults. Predictive analytics enables Home Credit to identify low-risk borrowers more effectively, reduce financial losses, and expand credit access responsibly.

## Project Objective
The goal of this project is to build a predictive model that estimates the likelihood of a loan applicant defaulting on their payments. Because many applicants lack traditional credit histories, the model incorporates alternative data sources such as:

- Transactional behavior  
- Demographic attributes  
- Telecommunications patterns  

By improving risk assessment for nontraditional applicants, Home Credit can make better-informed lending decisions while promoting financial inclusion.

## Proposed Solution
Our exploratory data analysis (EDA) and feature engineering revealed that an auxiliary dataset was critical for distinguishing creditworthy applicants. By merging multiple datasets and leveraging engineered features, we produced more accurate predictions of default risk.

This multi-source approach helps Home Credit uncover deeper insights into applicants who might be overlooked by standard credit scoring methods.

## Contribution
My contributions included:

- Creating the **joined dataset** that formed the foundation of our predictive modeling.
- Building the **baseline logistic regression model** used to benchmark future models.
- Fine-tuning the **final model** to improve predictive accuracy.
- Participating in data cleaning and feature engineering to ensure high-quality inputs.

These efforts strengthened both model performance and interpretability throughout the project.

---

## Project Files

### **Home Credit Project – EDA**
Explores the primary Kaggle datasets through cleaning, visualization, and feature exploration to understand factors influencing loan defaults.

### **Home Credit Project – EDA (Joined)**
Extends the initial analysis by merging supplemental datasets to surface deeper relationships and insights that support stronger model performance.

### **Home Credit Project – Logistic Regression Model**
Builds and evaluates a logistic regression model to predict loan defaults. Using predictors such as income, credit history, and asset ownership, the model achieved **72% accuracy**.

This baseline model supports data-driven lending decisions that enhance risk assessment and streamline the loan approval process.

---

## Business Value
Our model enables Home Credit to **accurately identify an additional 29% of applicants** who would otherwise be denied credit using application data alone.

This improvement in prediction accuracy represents an estimated **$61 million in additional revenue**, while simultaneously expanding access to credit for underserved individuals.  
The result is a dual benefit: improved financial inclusion *and* increased profitability.

---

## Challenges Faced

### **Computational Constraints**
The main application dataset contained over 300,000 applicants, creating computational strain. We mitigated this by:

- Downsampling  
- Removing redundant variables  
- Eliminating predictors with excessive missing values  

These steps kept the dataset manageable while preserving meaningful information.

### **Kaggle Submission Issues**
We encountered an unexpected error when submitting predictions to Kaggle. Through troubleshooting, we identified and resolved the issue, ensuring a valid submission.

---

## Takeaways
This project provided hands-on experience applying predictive analytics within the lending industry. Key learnings included:

- How to integrate multiple datasets to understand applicant behavior  
- The importance of feature engineering and data cleaning at scale  
- Techniques for building and refining machine learning models  
- How alternative data can reduce barriers for unbanked individuals  

Ultimately, this project connected my knowledge of the banking industry with my analytical skill set, producing a model that increased approval rates while maintaining acceptable risk levels.
