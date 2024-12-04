# Predicting the Impact of Climate Change on Global Crop Yields Using Machine Learning

## Problem Definition

This project aims to predict the impact of climate change on global crop yields, focusing on potatoes and maize. Climate change has profound implications for agriculture, which is critical to global food security. Understanding how climate factors---such as rainfall, temperature, and CO₂ emissions---affect crop productivity can provide valuable insights to help policymakers, farmers, and researchers develop strategies for sustainable agriculture and climate adaptation.

## Data Collection and Refinement

### Data Sources:

Rainfall and temperature data: World Bank. Crop yield data: Food and Agriculture Organization (FAO). CO₂ emissions data: Our World in Data. \### Data Refinement: The datasets were refined through log transformation to address skewness, ensuring more symmetric distributions suitable for analysis. Key variables such as average temperature and CO₂ emissions were selected for their significant impact on yields. Relationships between climate indicators (e.g., rainfall, CO₂ emissions) and crop yields were visualized using scatterplots, boxplots, and trend analysis.

## Implementation

### Predictive Modeling Techniques:

Random Forest Regression: Used to predict crop yields and identify variable importance. Logistic Regression: Used to classify high versus low crop yields based on median thresholds.

### Feature Selection:

Average temperature and CO₂ emissions were identified as the most critical factors influencing yields. Rainfall showed moderate importance, while pesticide usage contributed the least.

### Data Preprocessing:

Log transformations were applied to reduce skewness. Normalization techniques were used to handle outliers in CO₂ emissions and rainfall data.

## Evaluation

### Evaluation Metrics:

Regression Models: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R², and Mean Absolute Percentage Error (MAPE). Classification Models: Accuracy, confusion matrix, and classification reports.

### Results:

#### Random Forest Regression achieved high accuracy:

Potatoes: 98.79% Maize: 97.96%

#### Logistic Regression

Logistic Regression underperformed with an accuracy of 50.93%. The high performance of Random Forest highlights its ability to capture complex relationships between climate variables and crop yields.

#### Positive Results:

The project produced clear, actionable results. Random Forest models demonstrated strong predictive accuracy, achieving 98.79% accuracy for potatoes and 97.96% for maize. The results underscore the effectiveness of machine learning in capturing complex relationships between climate factors and crop yields. Graphical outputs, including scatterplots of predicted vs. actual values, indicate strong model performance, with predictions closely aligning with actual crop yields.

#### Negative Results:

Logistic Regression was significantly less effective, achieving only 50.93% accuracy. This result was clearly acknowledged, highlighting the model's limitations in capturing non-linear and complex relationships.
