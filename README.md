# Restaurant Tips Analysis (Excel)

## Tools Used
- Microsoft Excel

## Project Overview
This project focuses on analyzing and predicting restaurant tip amounts using Excel. The dataset contains information on customer characteristics, visit timing, and bill details. The analysis includes data cleaning, exploratory data analysis, regression modeling, and dashboard creation to understand tipping behavior and key influencing factors.

## Objective
- Estimate tip amounts based on total bill, gender, day, smoker status, group size, and time
- Summarize insights using pivot tables and charts
- Build a regression model to identify key drivers of tips
- Present findings through a clear and interactive dashboard

## Dataset Description
The dataset includes:
- Total bill amount  
- Tip amount  
- Customer gender  
- Smoking status  
- Day of visit  
- Time of visit (Lunch/Dinner)  
- Group size  

## Data Preparation
- Removed duplicate records
- Encoded categorical variables into numeric values for regression analysis
- Applied formatting such as bold headers and borders for better readability and structure

## Exploratory Data Analysis
- Created pivot tables to analyze total tips by gender  
  - Male customers contributed $485 in total tips
  - Female customers contributed $245 in total tips
- Analyzed tipping behavior by gender and meal time
  - During dinner, males tipped $390.96 and females tipped $156.11
  - During lunch, males tipped $95.11 and females tipped $88.40
- Visualized findings using pie charts and bar charts
- Performed correlation analysis
  - Total bill (0.675) and group size (0.488) show positive correlations with tip amount, with total bill showing the stronger relationship.
  - Gender, smoker status, day, and time show negligible correlation with tips

## Model Building
- Built a multiple linear regression model to predict tip amounts, explaining 46.9% of their variation (R² = 0.469).
- The model is statistically significant (F = 34.72)
- Key findings:
  - Total bill amount is a statistically significant positive predictor of tip amount (coefficient: 0.09437).
  - Group size has a positive estimated coefficient (0.1739), but it is not statistically significant at the 5% level (p-value: 0.0516).
  - Gender, smoking status, day, and meal time are not statistically significant predictors.
## Dashboard
An interactive dashboard was created to summarize insights:
- Total customers: 243
- Average total bill: $20
- Average tip: $3
- Visualizations included:
  - Pie chart: Tip contribution by gender
  - Bar chart: Tips by gender and meal time
  - Scatter plot: Predicted vs actual tips
  - Column chart: Tip totals by day

Key dashboard insights:
- Weekend days (Saturday and Sunday) generate the highest total tips
- Dinner hours contribute the majority of tips
- Male customers contributed higher total tips than female customers in the analyzed dataset.

## Conclusion
The analysis reveals that total bill amount has a statistically significant positive relationship with tip amounts. Group size also shows a positive relationship, but it is not statistically significant at the 5% level. Although higher total tips were observed during weekends and dinner hours, these patterns do not establish that these factors independently influence tipping behaviour. The regression model explains 46.9% of the variation in tip amounts.
