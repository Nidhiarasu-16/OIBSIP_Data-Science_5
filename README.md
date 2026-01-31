# Sales Prediction

Project Overview :
This project focuses on building a machine learning based sales prediction system using Python. The objective is to predict future product sales based on advertising expenditure across different marketing channels. The project demonstrates a complete Data Science workflow, including data understanding, exploratory data analysis (EDA), data preparation, model training, evaluation, and prediction for custom advertising inputs.

Objectives :
- To analyze the relationship between advertising expenditure and product sales
- To identify which advertising platforms contribute most to sales performance
- To preprocess and prepare numerical data for machine learning models
- To build a supervised regression model for sales prediction
- To evaluate model performance using appropriate regression metrics
- To enable sales prediction for custom, user-defined advertising budgets

Dataset Description :
- The dataset contains historical advertising and sales data
- Each row represents a single advertising scenario
- Advertising spend is recorded across multiple platforms

Key Features :
- Input Features (Independent Variables) :
    - TV : Advertising spend on TV
    - Radio : Advertising spend on radio
    - Newspaper : Advertising spend on newspapers
- Target Variable (Dependent Variable) :
    - Sales : Product sales (continuous numerical value)

Problem Type :
- Supervised Learning
- Regression Problem
- The target variable is continuous, requiring regression-based machine learning models

Tools and Technologies :
- Programming Language : Python
- Development Environment : Jupyter Notebook / VS Code

Libraries Used :
  1. NumPy – numerical computations
  2. Pandas – data manipulation and analysis
  3. Matplotlib & Seaborn – data visualization
  4. Scikit-learn – model training, evaluation, and data splitting

Methodology :
  1. Data Understanding :
      - Inspected dataset structure, feature types, and data dimensions
      - Identified advertising spend variables as inputs and sales as the target variable
  2. Exploratory Data Analysis (EDA) :
      - Analyzed statistical summaries of advertising and sales data
      - Visualized relationships between advertising platforms and sales using scatter plots
      - Examined correlations to identify influential advertising channels
  3. Data Preparation :
      - Selected relevant features and target variable
      - Split data into training and testing sets using an 80:20 ratio
      - Ensured reproducibility using a fixed random state
  4. Model Building :
      - Trained a Linear Regression model to learn relationships between advertising spend and sales
      - Interpreted regression coefficients to understand feature importance
  5. Model Evaluation :
      - Evaluated model performance using regression metrics :
      - Mean Absolute Error (MAE)
      - Mean Squared Error (MSE)
      - R² Score
      - Compared predicted sales against actual sales to assess model accuracy
  6. Prediction :
      - Enabled sales prediction for custom advertising budgets
      - Implemented predictions for user-defined TV, Radio, and Newspaper spend values

Key Insights :
  1. TV advertising has the strongest influence on product sales
  2. Radio advertising shows a moderate positive impact
  3. Newspaper advertising contributes minimally to sales prediction
  4. Linear Regression provides a strong baseline model for sales forecasting
  5. Advertising spend can be effectively used to estimate future sales performance

Conclusion :
This project demonstrates how machine learning regression techniques can be applied to predict product sales based on advertising expenditure. By combining exploratory data analysis with interpretable models like Linear Regression, the system provides actionable business insights and reliable sales forecasts. The project serves as a strong foundational example for understanding regression-based Data Science workflows and real-world business prediction problems.
