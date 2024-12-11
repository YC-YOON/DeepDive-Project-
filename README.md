# Predicting Unemployment Rate in California

## Team Members
- Xinrui Chen - xinruic2@illinois.edu
- MJ Cho - minjae5@illinois.edu
- Claire Chou - czchou2@illinois.edu
- Young Chul Yoon - ycyoon2@illinois.edu

## Problem Statement
This project aims to leverage a dataset containing statistics on the total labor force, unemployment, and employment figures to develop a predictive model. By analyzing these features, we hope to forecast employment trends in California over the coming decade, aiding individuals in making informed decisions about their options within the state.

# Unemployment Rate Prediction in California

Unemployment rates are critical indicators of economic health, providing valuable insights into labor market dynamics and influencing policy decisions. California, one of the largest and most economically diverse states in the United States, has a complex labor market shaped by various demographic, geographic, and economic factors. Accurate prediction of unemployment rates in California is essential for policymakers, businesses, and researchers to make informed decisions and implement effective strategies.

## Project Overview

This project aims to analyze a dataset containing historical and socio-economic variables to predict unemployment rates in California. The dataset provides predictors that capture trends in the labor market. We implemented and evaluated three machine learning techniques to model these relationships:

### Machine Learning Methods

1. **Linear Regression**  
   A baseline approach to model the linear relationships between predictors and the unemployment rate.  
   *Reference*: [Su et al., 2012](https://doi.org/10.1016/j.ecoinf.2012.03.004)

2. **Logistic Regression**  
   Adapted to analyze categorical trends in the dataset, offering insights into threshold-based predictions (e.g., above or below specific unemployment levels).  
   *Reference*: [Kleinbaum et al., 2002](https://doi.org/10.1007/b97377)

3. **Recurrent Neural Networks (RNNs)**  
   A deep learning technique that leverages sequential data to capture temporal dependencies and provide dynamic predictions.  
   *Reference*: [Salehinejad et al., 2017](https://doi.org/10.1109/ACCESS.2017.2761719)

### Data Exploration and Analysis

We conducted comprehensive data exploration to uncover trends, correlations, and patterns within the dataset. This step provides a deeper understanding of the underlying structure and supports the development of robust prediction models.

## Objectives

- **Model Performance Comparison**: Evaluate the predictive performance of linear regression, logistic regression, and RNNs.
- **Strengths and Limitations**: Highlight the advantages and drawbacks of each method in the context of unemployment forecasting.
- **Economic Insights**: Offer insights into effective techniques for predicting unemployment rates, focusing on the unique challenges of California's labor market.

## Key Features

- **Data Analysis**: Comprehensive exploration of the dataset to identify meaningful patterns and correlations.
- **Predictive Models**: Implementation of three distinct machine learning techniques to capture different aspects of unemployment trends.
- **Forecasting Focus**: Emphasis on temporal dependencies and threshold-based predictions to support informed decision-making.

## Conclusion

This project contributes to the growing field of machine learning applications in economic forecasting. By addressing the specific challenges of California's diverse labor market, it provides actionable insights for policymakers, businesses, and researchers.

---

For more details, please refer to the dataset documentation and the source code included in this repository.


## License
This project is licensed under the terms of the [MIT License](LICENSE.txt). See `LICENSE.txt` for more information.
