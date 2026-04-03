# Real Estate Price Prediction Model 
A machine learning project that predicts housing prices using structured real estate data. This model leverages feature engineering, location clustering, and ensemble learning (Random Forest) to capture complex relationships in housing markets.

## Overview
This project builds a regression model to estimate property prices based on features such as location, size, number of bedrooms/bathrooms, and property type. 
Key highlights: 
- Advanced feature engineering (price per sqft, bed/bath ratio)
- Location-based clustering using KMeans
- Handling high-cardinality categorical variables
- End-to-end preprocessing pipeline
- Random Forest regression model for prediction  

## Features & Techniques 
### Feature Engineering
- Price per Square Foot
- Bed-to-Bath Ratio
- Outlier handling using clipping

### Location Intelligence 
- KMeans clustering on latitude/longitude to create location zones

### Categorical Handling 
- Reduces high-cardinality features by keeping top categories and grouping others into 'Other'
- One-hot encoding for categorical variables ### Preprocessing Pipeline
- 'ColumnTransformer' for: Standard scaling (numeric features), One-hot encoding (categorical features)

### Model 
- Random Forest Regressor
- 500 trees
- Max depth of 20
- Captures nonlinear relationships and interactions

## Installation 
Clone the repository: 

```bash
git clone https://github.com/arav-kamat/real-estate-price-prediction.git
cd real-estate-price-prediction
