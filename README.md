# A Statistical Study on Crop Production and Yield Prediction Using Remote Sensing Data
## DS5500 - Capstone Project - Northeastern University

## Summary
In agriculture, predicting crop yields is essential for making informed decisions about farming practices. This project aims to develop an integrated solution for accessing yield predictions and exploring crop yield data along with interactive visualizations, including crop disease prediction. The project utilizes time series forecasting models such as ARIMA, Multivariate LSTM, and image-based deep neural networks to predict crop yield. The report focuses on extending the project to include soybean yield prediction using remote sensing data for Illinois, USA.

## Datasets Overview
The project utilizes various datasets acquired from sources like the Food and Agriculture Organization (FAO) database, World Data Bank, and Earth Engine's public data archive. These datasets include yield data, temperature, pesticide usage, agricultural land area, fertilizer usage, rainfall, and remote sensing data such as MODIS imagery. Data cleaning, preprocessing, and feature engineering were performed to extract relevant features for analysis.

## Methods
### Data Preprocessing
Data preprocessing involved cleaning and selecting relevant features, grouping unique items (crops), and modifying their names for ease of use. The data was scaled using MinMaxScaler to bring features to the same level of magnitude.

### Statistical Analysis and Yield Prediction
Statistical analysis and yield prediction were performed using time series models such as ARIMA and Multivariate LSTM. Univariate time series with ARIMA and multivariate forecasting with LSTM were implemented to predict yield values.

### Remote Sensing Data and Yield Prediction
Remote sensing data, including MODIS imagery, was used for yield prediction in Illinois, USA. The data collection involved gathering surface reflectance, land surface temperature, daily weather data, and land cover type. A CNN-LSTM architecture was developed to extract relevant features from images and handle long-time lags between images.

## Results
The LSTM model outperformed other regression models like Random Forest, LightGBM, and XGBoost in terms of RMSE. Additionally, the CNN-LSTM architecture showed promising results for yield prediction using remote sensing data. Interactive visualizations were created to visualize crop yield across countries and years.

## Discussion
Deep learning techniques like LSTMs showed superior performance in predicting future yield data over other machine learning techniques. Multivariate regression offered better results by incorporating information from other features. The CNN-LSTM architecture performed well for yield prediction using remote sensing data, offering advantages in areas with limited agricultural documentation.

The results of the project can be accessed in the below link
https://sites.google.com/view/crop-yield-analysis-prediction/home
