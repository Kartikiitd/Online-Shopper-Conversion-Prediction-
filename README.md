

# Online Shopper Conversion Prediction

This project focuses on predicting whether a user will complete a purchase based on their website activity and behavioral patterns. The work blends classical machine learning with hands-on data preprocessing and modeling.

## 📊 Key Features

* **Comprehensive EDA**: Explored distributions, handled outliers, and visualized patterns across categorical and numerical features.
* **Data Preprocessing**:

  * Custom binning of numerical features
  * One-hot encoding for categorical variables
  * Z-score normalization for scaling
* **Model Development**:

  * Implemented Logistic Regression from scratch for interpretability
  * Compared with advanced ensemble models (Bagging, Boosting)
* **Feature Engineering & Imbalance Handling**:

  * Created meaningful features to capture visitor intent
  * Used techniques like class weighting and resampling
* **Performance**:

  * Best F1 Score: **0.66** using Gradient Boosting

## 🧠 Models Used

* Logistic Regression (custom implementation)
* Random Forest (Bagging)
* Gradient Boosting (XGBoost/LightGBM)
* Comparison based on precision, recall, and F1 score

## 🗂 Dataset

* Contains user session data: visit duration, bounce rate, exit rate, page values, and categorical info like month, traffic type, etc.
* Target variable: `Revenue` (whether a purchase was made)

