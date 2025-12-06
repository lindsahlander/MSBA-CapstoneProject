# Swire Coca-Cola Cart Abandonment Analysis

## Business Problem

Swire Coca-Cola has recently implemented a new checkout system called MyCoke360. In doing so, they have observed an interesting pattern in customer behavior where a significant number of customers are abandoning their carts before completing purchases. Understanding the factors contributing to this cart abandonment is crucial for improving customer experience and increasing sales. 

## Project Objective

The goal of this project is to analyze customer data to identify patterns and factors that lead to cart abandonment. By building predictive models, we aimed to identify characteristics of customers who are likely to abandon their carts, enabling Swire Coca-Cola to implement targeted strategies to reduce abandonment rates. The bulk of our analysis focused on developing a logistic regression model which enabled us to identify statistically significant predictors of cart abandonment. This allowed us to paint a clearer picture of customer behavior and provided actionable insights for the business.

The logistic regresssion model also helped inform our association rules mining efforts, allowing us to uncover relationships between different customer attributes and cart abandonment behavior. This allowed us to identify what we called "friction loops" in which customers would get stuck in the checkout process and ultimately abandon their carts.

## Proposed Solution

To address the business problem, we proposed the following solution:

1. **Data Collection and Cleaning**: Gathered relevant customer data from the MyCoke360 system, ensuring it was clean and ready for analysis.
2. **Exploratory Data Analysis (EDA)**: Conducted EDA to understand the distribution of variables and identify potential predictors of cart abandonment. This included visualizations and summary statistics that helped inform our modeling approach.
3. **Feature Engineering**: Created new features based on existing data and Swire's definition of cart abandonment identify targets.
4. **Model Development**: Built a logistic regression model to predict cart abandonment, using the engineered features as inputs. We then created association rules to further explore relationships in the data. 
5. **Model Evaluation**: Assessed the model's performance using appropriate metrics such as accuracy, precision, recall, and AUC-ROC to ensure its reliability.
6. **Insights and Recommendations**: Analyzed the model results to identify key factors contributing to cart abandonment and provided actionable recommendations to Swire Coca-Cola for reducing abandonment rates.

## Contribution

My contributions included:

- Creating the **joined dataset** that formed the foundation of our predictive modeling.
- Building the **baseline logistic regression model** used to benchmark future models.
- Conducting **correlation analysis** to identify key predictors of cart abandonment.
- Participating in data cleaning and feature engineering to ensure high-quality inputs.

These efforts strengthened both model performance and interpretability throughout the project.

## Business Value

By identifying the key factors contributing to cart abandonment, Swire Coca-Cola can implement targeted strategies to improve the checkout experience. This could lead to increased conversion rates, higher customer satisfaction, and ultimately, greater revenue. The insights gained from the logistic regression model and association rules mining provide a data-driven foundation for making informed business decisions.

## Challenges Faced

During the project, we encountered several challenges:

- **Data Quality**: Ensuring the data was clean and free from inconsistencies required significant effort in data preprocessing.
- **Data Engineering**: In order to accurately identify cart abandonment, we had to engineer features that aligned with Swire's specific definitions and business context. This required close collaboration in order to ensure that we were accurately identifying abandoned carts.
- **Imbalanced Classes**: Cart abandonment events were relatively rare compared to completed purchases, leading to class imbalance issues that needed to be addressed in the modeling process.

## Takeaways

This project gave me the opportunity to collaboarte with team members and stakeholders in order to solve a real-world business problem. I gained valuable experience in data cleaning, feature engineering, and logistic regression modeling. Additionally, I learned the importance of aligning data analysis with business objectives to ensure that insights are actionable and relevant. Overall, this project enhanced my skills in predictive modeling and provided a deeper understanding of customer behavior in e-commerce contexts.
