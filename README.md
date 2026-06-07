Jakarta Air Quality (ISPU) Temporal Forecaster

Description
This repository contains an end-to-end time-series forecasting pipeline designed to predict the Air Pollution Standard Index (ISPU) in Jakarta. Utilizing historical environmental data from 2010 to 2025, the project systematically benchmarks five machine learning architectures to identify the most robust model for atmospheric prediction. The final optimized model achieves a baseline Mean Absolute Percentage Error (MAPE) of 5.31%.

Highlights
- Applied the Knowledge Discovery in Databases (KDD) framework to 15 years of historical time-series data to forecast Jakarta's Air Pollution Standard Index.  
- Engineered robust data preprocessing pipelines utilizing linear interpolation and median smoothing to mitigate sensor noise, alongside chronological data splitting for strict temporal validation.
- Extracted temporal dependencies by developing custom lag features and seasonal encodings prior to scaling.  
- Automated algorithmic benchmarking across five models (SVR, KNN, Random Forest, Gradient Boosting, Linear Regression), identifying Linear Regression as the most robust architecture.  
- Achieved a highly accurate Mean Absolute Percentage Error (MAPE) of 5.31%, actively mitigating the local noise overfitting and spiky overshoot observed in complex ensemble models like Random Forest
