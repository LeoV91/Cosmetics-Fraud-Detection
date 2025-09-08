# Cosmetics-Fraud-Detection

# Payment Card Fraud Detection

This Jupyter Notebook demonstrates a comprehensive approach to detecting fraudulent transactions in the luxury cosmetics sector. It includes data preprocessing, feature engineering, handling class imbalance, and training multiple machine learning models. The goal is to identify fraudulent transactions effectively while minimizing false positives and negatives.

## Key Features

1. **Data Exploration**:
   - Initial inspection of the dataset, including data types, missing values, and distributions of key features.

2. **Feature Engineering**:
   - Creation of new features such as temporal attributes, high-cost purchase flags, and binary indicators for VIP customers.
   - Decomposition of complex fields like `Store_ID`, `Product_SKU`, and `IP_Address` into more granular components.

3. **Data Cleaning**:
   - Handling missing values and ensuring consistent data types.
   - Standardizing column names for ease of use.

4. **Class Imbalance Handling**:
   - Oversampling the minority class (`fraud_flag`) to balance the dataset.

5. **Model Training and Evaluation**:
   - Training a variety of models, including Logistic Regression, Decision Trees, Random Forests, Gradient Boosting, and XGBoost.
   - Using a preprocessing pipeline with `StandardScaler` for numerical features and `TargetEncoder` for categorical features.
   - Evaluating models with accuracy and detailed classification reports.

6. **Visualization**:
   - Distribution plots for key features to understand data patterns.

## Results

- Ensemble models like Random Forest, Gradient Boosting, and XGBoost achieved the highest accuracy and recall, making them the most effective for fraud detection.
- Logistic Regression served as a reliable baseline, while KNN and SVM also performed competitively.

## Future Directions

- Hyperparameter optimization for the best-performing models.
- Exploration of advanced feature engineering and external data sources.
- Implementation of cost-sensitive modeling to account for the financial impact of misclassifications.
- Experimentation with time-series modeling and anomaly detection techniques.

## How to Use

1. Clone the repository and install the required dependencies.
2. Load the dataset into the `archive/` directory.
3. Run the notebook to preprocess the data, train models, and evaluate results.

This project provides a robust framework for fraud detection and can be adapted to other domains with similar challenges.
