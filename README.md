# Bank_Customer_Churn
This project analyzes customer churn data for a bank to predict which customers are likely to leave the bank's services. The notebook explores the dataset, performs data visualization, and implements machine learning models to predict customer churn.

## Features
- Data loading and exploration
- Data visualization using Matplotlib and Seaborn
- Data preprocessing (label encoding, feature scaling)
- Machine learning model implementation:
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting Classifier
- Model evaluation metrics (accuracy, classification report, confusion matrix)

## Dataset
The dataset used is `Churn_Modelling.csv` containing:
- Customer demographics (age, gender, geography)
- Bank account details (balance, tenure, credit score)
- Product usage (number of products, credit card status)
- Activity indicators (active membership status)
- Target variable: `Exited` (whether customer left the bank)

## Requirements
- Python 3.x
- Libraries:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn

## Usage
1. Clone the repository
2. Install required libraries: `pip install numpy pandas matplotlib seaborn scikit-learn`
3. Run the colab file `Bank_Customer_Churn.ipynb`

## Results
The notebook demonstrates:
- Exploratory data analysis of customer churn patterns
- Visualization of key features affecting churn
- Performance comparison of different machine learning models

## Future Improvements
- Feature engineering to create more predictive features
- Hyperparameter tuning for better model performance
- Implementation of neural networks or other advanced models
- Deployment as a predictive service

## Group Members
- Gajal Garg (SAP ID - 500109972)
- Samriddh Sharma (SAP ID - 500109805)
