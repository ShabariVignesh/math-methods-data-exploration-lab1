# math-methods-exploration-lab1

# Coronary Heart Disease (CHD) Data Analysis

## Introduction
Coronary heart disease (CHD) is a leading cause of morbidity and mortality globally. This project aims to analyze a dataset containing various health and behavioral attributes to identify patterns and correlations associated with CHD. The analysis includes exploratory data analysis, visualization, and predictive modeling.

## Objectives
- To classify the dataset variables into distinct categories (continuous, categorical, nominal).
- To perform exploratory data analysis (EDA) to understand the distribution and relationships of variables.
- To employ predictive modeling techniques to forecast CHD risk based on health metrics.

## Datasets Used
1. `heart-train.csv`
2. `heart-test.csv`

## Methodology
### Data Exploration
1. **Variable Classification**: 
   - Continuous: `sbp`, `tobacco`, `ldl`, `adiposity`, `typea`, `obesity`, `alcohol`, `age`
   - Categorical/Nominal: `famhist`, `chd`
2. **Descriptive Statistics**: Statistical details such as mean, median, range, and standard deviation were computed for continuous variables.
3. **Missing Values**: Checked for and confirmed the absence of missing values in the dataset.
4. **Visualization**: Created various plots including histograms, box plots, scatter plots, and heatmaps to visualize data distributions and relationships.

### Predictive Modeling
1. **Logistic Regression**: Employed logistic regression to predict the occurrence of CHD. 
   - Achieved training accuracy: 77.20%
   - Achieved testing accuracy: 67.47%
   - Mean squared error: 0.33
2. **Statistical Tests**:
   - **Shapiro-Wilk Test**: Confirmed non-normal distribution of the `price` feature.
   - **T-Test**: Significant difference in sale prices of properties built before and after 1990.
   - **ANOVA**: Significant difference in sale prices among houses built in 1990, 2000, and 2010.

## Key Findings
- **Age**: Positive correlation with CHD, indicating higher CHD incidence with increasing age.
- **Tobacco Consumption**: Higher consumption associated with increased CHD risk.
- **LDL Cholesterol**: Higher LDL levels correlated with higher CHD risk.
- **Adiposity**: Positive trend observed with CHD occurrence.
- **Predictive Model**: Logistic regression demonstrated reasonable accuracy in predicting CHD.

## Future Work
- **Advanced Feature Engineering**: Explore more sophisticated feature engineering techniques to improve model performance.
- **Complex Models**: Implement more complex machine learning models such as decision trees, random forests, or neural networks.
- **Hyperparameter Tuning**: Optimize model parameters for better predictive accuracy.

## Conclusion
This analysis highlights the importance of regular health assessments and lifestyle modifications, especially for older adults and those with higher tobacco consumption and LDL levels. By identifying and mitigating these risk factors, individuals can potentially reduce their risk of developing CHD.

