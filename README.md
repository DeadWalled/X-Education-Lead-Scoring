
# X Education Lead Scoring Model
Abhishek Singh Dhadwal
## Project Overview
X Education, an online education company, aims to improve its lead conversion rate to maximize the efficiency of its sales process. Despite acquiring a significant number of leads, the company faces a challenge with a conversion rate of around 30%. The goal of this project is to identify the most promising leads, termed 'Hot Leads', to achieve a target lead conversion rate of approximately 80%.

## Problem Statement
The primary objective is to build a logistic regression model that assigns a lead score between 0 and 100 to each lead. This score will help the company in prioritizing leads that are more likely to convert into paying customers. Additionally, the model should be adaptable to the company's evolving requirements.

## Dataset
The dataset provided contains around 9000 data points with attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. The target variable, 'Converted', indicates whether a lead was successfully converted (1) or not (0).

## Goals of the Case Study
- **Model Development**: To develop a logistic regression model that assigns a lead score to each lead based on their likelihood of conversion.
- **Adaptability**: Ensure the model is flexible to accommodate future changes in the company's requirements.

## Methodology
1. **Data Preparation**: Handling missing values, especially the 'Select' level in categorical variables, which is treated as a null value.
2. **Exploratory Data Analysis (EDA)**: Analyzing the dataset to uncover insights and patterns that influence lead conversion rates.
3. **Data Cleaning and Preprocessing**: Imputing missing values, encoding categorical variables, and feature scaling.
4. **Model Building**: Developing a logistic regression model to predict lead conversion and assign lead scores.
5. **Model Evaluation**: Assessing the model's performance using metrics such as accuracy, precision, recall, and AUC-ROC.
6. **Insights and Recommendations**: Deriving business insights from the model's coefficients and making recommendations for targeting potential leads.

## Repository Contents
- `Lead Scoring v2.ipynb`: Jupyter notebook containing the logistic regression model, conversion predictions, and evaluation metrics.
- `Assignment Subjective Questions Answered.pdf`: Document with solutions to the company's specific problems, based on the logistic regression model.
- `Lead Scoring Presentation.pdf`: Presentation outlining the analysis approach, results, and business recommendations.
- `Lead Conversion Analysis Project Summary Report.pdf`: A summary report explaining the methodology, analysis, and key learnings from the project.

## Key Findings
- The logistic regression model successfully assigns lead scores, identifying 'Hot Leads' with a higher likelihood of conversion.
- Key predictors of lead conversion include 'Total Time Spent on Website', 'Lead Origin', and 'Lead Source'.
- The model's flexibility allows for adjustments based on the company's changing requirements, ensuring its long-term applicability.

## Conclusion
The logistic regression model developed in this project enables X Education to prioritize leads more effectively, thereby potentially increasing the lead conversion rate significantly. By focusing on 'Hot Leads', the sales team can allocate their efforts more efficiently, improving both productivity and conversion outcomes.