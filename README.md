# Analysis and Prediction of Arctic Climate Variables (atmospheric CO₂ concentration, sea ice extent and area, and global surface temperature changes)

This project aims to analyze key Arctic climate variables, such as atmospheric CO₂ concentration, sea ice extent and area, and global surface temperature changes, and build a predictive model to understand their relationships.

## Data Collection and Preparation 
Data were collected from reliable sources such as NASA and NSIDC, including yearly and monthly measurements of CO₂ levels, sea ice extent/area in Arctic region, and surface temperature changes spanning from 1885 to 2024. The datasets were cleaned, relevant columns selected, and missing or incomplete data points (e.g., 1958 and partial years) were excluded to ensure data quality.

## Data Analysis
Correlation analysis was conducted using heatmaps and pairplot to visualize relationships between variables. This exploratory analysis revealed strong correlations, especially between CO₂ levels and temperature changes, supporting known climate science observations.

## Machine Learning Model
A linear regression model was trained to predict global surface temperature change using CO₂ average, sea ice extent, and sea ice area as predictors. The data were split into training (75%) and testing (25%) sets, and standard scaling was applied to features to normalize their ranges. The model achieved an R² score of approximately 0.92, indicating that 92% of temperature variation is explained by the input features. The root mean squared error (RMSE) of 0.0886 °C demonstrated high prediction accuracy.

## Conclusion
This project demonstrates how machine learning techniques can effectively model complex climate relationships in the Arctic region. The results reinforce the strong influence of CO₂ and sea ice metrics on temperature change and provide a basis for further research and more sophisticated predictive modeling.
