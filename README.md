# WHOOP Data Analysis: Health and Performance Optimization

## Project Overview
This project utilizes data from WHOOP wearables to analyze and optimize health and performance metrics. By examining the effects of sleep duration, day strain, heart rate variability, and temperature on recovery and sleep quality, this project provides actionable insights for enhancing wellness and athletic performance. Advanced techniques in data science—including A/B testing, feature engineering, and machine learning—were applied to uncover relationships and build predictive models.

---

## Table of Contents
1. [Project Objectives](#project-objectives)
2. [Data Processing](#data-processing)
3. [Feature Engineering](#feature-engineering)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [A/B Testing](#a-b-testing)
6. [Machine Learning Models](#machine-learning-models)
7. [Results and Insights](#results-and-insights)
8. [Conclusion and Future Work](#conclusion-and-future-work)

---

## Project Objectives
1. **Identify Patterns and Correlations**: Understand relationships between key physiological metrics (e.g., strain, HRV) and recovery.
2. **Hypothesis Testing**: Perform A/B tests to explore whether strain levels, sleep duration, and other factors significantly impact recovery and sleep quality.
3. **Predictive Modeling**: Build machine learning models to predict recovery scores based on physiological and activity data.
4. **Data Visualization**: Develop interactive dashboards to effectively communicate findings.

---

## Data Processing
- **Data Cleaning**: Addressed missing values and ensured consistency across datasets.
- **Date-Time Handling**: Converted columns like `Cycle start time` to datetime format for time-based segmentation.
- **Segmentation**: Split data by month and by strain levels for targeted analyses.

---

## Feature Engineering
- **Interaction and Polynomial Terms**: Added interaction terms and polynomial features to capture nonlinear relationships.
- **Standardization**: Scaled features to enhance model training and performance.
- **Additional Metrics**: Calculated metrics such as “sleep consistency” and weekly averages to capture physiological trends.

---

## Exploratory Data Analysis (EDA)

### Visualizations
- **Day Strain Distribution**: Histograms used to understand distribution and define thresholds.
- **Monthly Trends**: Visualized recovery, strain, and sleep quality by month to identify temporal patterns.
- **Correlation Heatmap**: Examined correlations among recovery, sleep duration, strain, HRV, and more.

---

## A/B Testing

### Hypotheses
1. **Strain and Recovery**: Compared recovery scores between high and low strain days. Result: No significant difference in recovery (p > 0.05).
2. **Sleep Duration Impact**: Tested the effect of sleep duration on recovery. Result: Longer sleep significantly improved recovery (p < 0.05).
3. **Heart Rate Variability and Sleep Quality**: Tested the impact of HRV on sleep performance. Result: Higher HRV associated with better sleep (p < 0.05).

### Statistical Methods
- **T-tests** and **Mann-Whitney U tests** were used for hypothesis testing.
- **Bonferroni Correction** applied to adjust for multiple comparisons.

---

## Machine Learning Models

### Models
1. **Random Forest Regressor**: Predicted recovery scores, achieving an R² of 0.27 after tuning.
2. **Gradient Boosting Regressor**: Modeled sleep performance with an R² of 0.19.

### Evaluation Metrics
- **R-squared**: Indicates variance explained by the model.
- **MAE** and **RMSE**: Used to quantify model accuracy.

---

## Results and Insights

1. **Sleep Duration and Recovery**: Longer sleep durations correlated with improved recovery scores.
2. **Impact of Strain on Sleep**: High day strain was linked to poorer sleep quality.
3. **Heart Rate Variability**: Higher HRV correlated with better sleep and recovery outcomes.
4. **Temperature Effects**: Elevated skin temperature slightly correlated with lower recovery, indicating potential stress.

---

