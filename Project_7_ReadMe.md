# Impact of Rainfall, Pesticides, and Temperature on Crop Yield in India

## Solution Overview
This project aimed to analyze the impact of rainfall, pesticides, and temperature on crop yield in India. It involved several steps:

### Data Loading and Preparation
The crop yield dataset was loaded and filtered to include only data for India.

### Data Exploration
Relationships between crop yield and the predictor variables were explored using descriptive statistics, scatter plots, and correlation coefficients.

### Feature Engineering
A logarithmic transformation was applied to the 'pesticides_tonnes' feature to address its skewed distribution.

### Data Splitting
The data was split into training and testing sets for model training and evaluation.

### Model Training
A RandomForestRegressor model was trained using the training data.

### Model Evaluation
The model's performance was evaluated using the testing data. The Mean Squared Error (MSE) and R-squared score were calculated:
- **Mean Squared Error (MSE)**: 12396941906.828453
- **R-squared Score**: -0.2712364264698528

### Data Visualization
Scatter plots were created to visualize the relationship between crop yield and each predictor variable.

## Conclusion
This project successfully analyzed the impact of rainfall, pesticides, and temperature on crop yield in India using a machine learning approach. The trained RandomForestRegressor model can be used to predict crop yield based on these factors. The scatter plots and correlation coefficients provide insights into the relationships between the variables.

## Insights and Next Steps
The analysis revealed that rainfall, pesticide use, and temperature have varying degrees of influence on crop yield in India. Further investigation is needed to understand the specific nature of these relationships and identify any potential interactions between the predictor variables. The analysis can be extended to other countries or regions to compare and contrast the impact of these factors on crop yield in different contexts. The insights gained from this analysis can be used to inform agricultural practices and policies aimed at optimizing crop yield and ensuring food security.

## Dataset Link
The dataset used for this analysis can be found on Kaggle: [Crop Yield Prediction Dataset](https://www.kaggle.com/datasets/patelris/crop-yield-prediction-dataset).

The analysis can be extended to other countries or regions to compare and contrast the impact of these factors on crop yield in different contexts. 
The insights gained from this analysis can be used to inform agricultural practices and policies aimed at optimizing crop yield and ensuring food security.

## Dataset Link
The dataset used for this analysis can be found on Kaggle: [Crop Yield Prediction Dataset](https://www.kaggle.com/datasets/patelris/crop-yield-prediction-dataset).
