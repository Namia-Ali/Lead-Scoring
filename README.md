# Lead Score Case Study: Logistic Regression

## Overview

This project involves building a predictive model for lead scoring using logistic regression. The goal is to identify the most promising leads that can be converted to paying customers for X Education, an online course provider.

## Problem Statement

X Education aims to improve its lead conversion rate, which currently stands at about 30%. The company wants to prioritize leads that are more likely to convert by assigning a lead score between 0 and 100. This score helps in distinguishing between 'hot' leads (more likely to convert) and 'cold' leads (less likely to convert).

## Business Objective

1. Understand and clean the provided data.
2. Conduct exploratory data analysis (EDA) to gain insights.
3. Build a predictive model using logistic regression.
4. Evaluate the model based on accuracy, sensitivity, specificity, precision, and recall.
5. Implement the model to make predictions on test data.

## Approach

1. **Data Understanding and Cleaning**: 
   - Analyze data attributes and remove columns with over 45% missing values.
   - Drop columns with high class imbalance or those not relevant to the business objective.
   - Impute missing values with mode or label them as unknown.
   - Treat outliers in numerical columns.

2. **Exploratory Data Analysis (EDA)**:
   - Investigate the relationship between different attributes and lead conversion rates.
   - Identify attributes such as 'Lead Add Form', 'API', 'Landing Page Submission', and 'Last Activity' that influence lead conversion.
   - Focus on attributes with high conversion rates for targeted lead generation.

3. **Model Building**:
   - Use logistic regression for predicting lead conversion.
   - Perform Recursive Feature Elimination (RFE) to select the top relevant features.
   - Evaluate the model using metrics such as accuracy, sensitivity, specificity, and ROC curve.

4. **Model Evaluation**:
   - The optimal threshold for lead conversion is found to be 0.3, with high sensitivity (91.41%), specificity (92.68%), and accuracy (92.2%).

## Results and Recommendations

1. Focus on leads from management specialization as they show a high conversion rate.
2. Prioritize leads that spend significant time on the website.
3. Target working professionals and leads coming through referrals.
4. Avoid focusing on unemployed individuals or students, as their conversion rates are lower.

## File Information

- **Lead_ppt_Final.pdf**: Presentation detailing the entire case study, including problem statement, approach, EDA, model building, evaluation, and recommendations.

## Getting Started

To explore this project:

1. Download the PDF file `Lead_ppt_Final.pdf` from this repository.
2. Review the slides to understand the problem, methodology, and results.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Make your changes and commit them: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-branch`
5. Submit a pull request.

## Contact

For more information, please contact:

**Namia Mohamed Ali**  
Email: [nami29221@gmail.com](mailto:nami29221@gmail.com)
