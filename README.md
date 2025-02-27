# Credit Card Default Prediction

This project predicts whether a customer will default on their credit card payment in the next month using a classification model.

## Features
- **Data Validation**: Ensures data quality using schema-based checks for filenames, columns, and datatypes.
- **Data Preprocessing**: Handles missing values, scales numeric features, and applies correlation analysis.
- **Clustering**: Groups customers using KMeans to improve model accuracy.
- **Model Training**: Uses Naïve Bayes and XGBoost, selecting the best model per cluster based on AUC scores.