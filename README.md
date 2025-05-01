# Multiple Linear Regression Analysis Tool

**Built by:** Deepanker Das (ICMR SRF)  
**Purpose:** To provide a user-friendly tool for performing multiple linear regression analysis, especially for researchers, students, and professionals who want to analyze their data without needing to write code. This tool simplifies the process of statistical analysis by providing key outputs, such as regression summaries, correlation plots, and variable importance.

## Overview

This Shiny web app was developed by **Deepanker Das**, an SRF at ICMR, to make complex statistical analysis easier and more accessible. The app helps users perform multiple linear regression analysis with just a few clicks, without requiring any prior programming knowledge. Whether you're working with healthcare data, survey results, or any other kind of structured dataset, this tool allows you to quickly get insights and make informed decisions.

## Why This Tool?

- **No Coding Required**: You don't need to know any programming. Simply upload your data, and the app will do the rest.
- **Fast Analysis**: Get quick statistical results, including regression models, p-values, R² values, and variable importance.
- **User-Friendly**: Designed for ease of use, even for those who don't have a background in statistics or programming.

This app makes it possible for non-coders to get meaningful insights from their data by automating the statistical analysis process.

## How to Use the Tool

### Step 1: Data Input

The app requires two Excel files:

1. **EXPLAIN.xlsx**: This file should contain your explanatory (independent) variables (predictors). These can be any variables you believe influence your response variables.
   
   - **Format**: Columns should represent variables, and rows should represent observations (data points).
   - **Example**: A dataset of factors affecting disease occurrence, with variables like age, sex, lifestyle factors, etc.

2. **RESPONSE.xlsx**: This file should contain your response (dependent) variables—the ones you are trying to predict or explain.
   
   - **Format**: Each column represents one response variable, and each row corresponds to an observation.
   - **Example**: Disease status, or any other outcome variable you are trying to predict.

### Step 2: Upload the Data

- Upload both **EXPLAIN.xlsx** and **RESPONSE.xlsx** files using the "Upload" buttons on the app interface.

### Step 3: Run the Analysis

- Once both files are uploaded, click the **"Run Analysis"** button.
- The app will automatically:
  - Perform multiple linear regression for each response variable using the explanatory variables.
  - Generate a **correlation plot** to show relationships between your explanatory variables.
  - Provide **regression summaries**, including coefficients, p-values, R², and Adjusted R².
  - Create **residual histograms** to help assess the fit of the models.
  - Generate **bar plots of variable importance** to show which explanatory variables most strongly affect each response.

### Step 4: Download the Results

The app allows you to download several key outputs for further analysis:

- **P-values Table (CSV)**: A CSV file containing the p-values for the regression coefficients. Helps identify which predictors are statistically significant.
- **R² Table (CSV)**: A CSV file containing R² and Adjusted R² values, which measure the goodness of fit of your models.
- **P-values with Stars (CSV)**: A CSV file that includes significance stars (***, **, *, .) for each p-value, indicating the level of statistical significance.
- **Grid of Variable Importance Plots (PNG)**: A PNG file with a grid of bar plots showing the variable importance for each response variable. This is useful for visualizing which explanatory variables have the most influence on your predictions.

## Output and Interpretation

Once the analysis is complete, the app provides the following outputs:

1. **Correlation Plot**: A graphical representation of the correlations between the explanatory variables. This helps identify multicollinearity or relationships between predictors.
2. **Regression Summaries**: Statistical summaries of the regression models for each response variable. It includes coefficients, p-values, R², and Adjusted R² values.
3. **Residual Histograms**: Histograms of residuals for each regression model, helping assess the normality of residuals and the fit of the model.
4. **Variable Importance Bar Plots**: Bar plots that show how important each explanatory variable is for predicting each response variable. This gives you a quick idea of which factors matter the most.

### Importance of This Tool

This tool is valuable for anyone who wants to perform regression analysis but does not have the time or expertise to write complex code. Here’s why it matters:

- **Accessibility**: Researchers, especially in fields like healthcare, social sciences, and education, can perform robust statistical analyses without needing to write code.
- **Efficiency**: Quickly analyze datasets and extract meaningful insights with minimal effort.
- **Informed Decision Making**: The app helps users make data-driven decisions based on rigorous statistical methods, such as understanding which variables influence the outcome the most.

By using this tool, users can gain a deeper understanding of the relationships in their data, which is crucial for making informed decisions in research, business, or policy-making.

## Conclusion

The Multiple Linear Regression Analysis Tool is designed to empower non-programmers to perform advanced statistical analyses without coding. Whether you are a researcher in public health, social sciences, or any other field, this tool can help you gain insights from your data and improve your analysis.

---

**Developed by**: Deepanker Das, SRF (ICMR)  
**License**: MIT License

For any issues or inquiries, please contact: [Your Contact Information]
