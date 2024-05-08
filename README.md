# Fraud-Detection-Credit-Card


## About the Dataset

### Description
This dataset features credit card transactions from cardholders in Europe for the year 2023, which is accessible through a Kaggle dataset. It includes more than 550,000 anonymized records to ensure the privacy of the cardholders. You can find the dataset here: [Kaggle Dataset](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023?resource=download).

### Key Features
- **id**: A unique identifier for each transaction.
- **V1-V28**: Anonymized variables that encode different attributes of the transactions like timing, location, etc.
- **Amount**: The value of the transaction.
- **Class**: A binary indicator where '1' signifies a fraudulent transaction and '0' signifies a non-fraudulent transaction.

### Reason for Choosing Logistic Regression
Logistic Regression was selected as the model for this analysis due to several key factors:
- **Binary Classification**: This method is ideal for binary classification tasks, which in this case is determining if a transaction is fraudulent.
- **Interpretability**: It offers interpretable results, making it possible to gauge the influence of each feature on the likelihood of fraud.
- **Stability**: It exhibits low variance and is generally robust to overfitting, particularly beneficial in scenarios with a high dimensionality.
- **Benchmarking**: It establishes a baseline for evaluating the performance of more complex machine learning algorithms.

### For more EDA
you can find the full EDA here: [EDA and Classifications](https://www.kaggle.com/code/demolaoyedeji/eda-and-classification-credit-card-fraud/notebook).
