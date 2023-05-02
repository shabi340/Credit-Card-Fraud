# Credit Card Fraud Detection

## About
This project is aimed at developing a model to detect credit card fraud using machine learning techniques. The dataset used is the Credit Card Fraud Detection dataset from Kaggle.

### Getting Started
1. To get started with this project, you will need to do the following:
2. Clone this repository to your local machine
3. Install the required packages using the requirements.txt file
4. Run the Jupyter notebook credit_card_fraud_detection.ipynb to explore the dataset and run the machine learning models.

### Prerequisites
To run this project, you will need to have the following packages installed:
1. pandas
2. numpy
3. matplotlib
4. seaborn
5. scikit-learn
6. xgboost

You can install these packages using the requirements.txt file provided in this repository.

### Project Structure
The project has the following structure:
1. credit_card_fraud_detection.ipynb: Jupyter notebook containing the code for the project
2. reditcard.csv: CSV file containing the dataset
3. README.md: This README file
4. requirements.txt: File containing the required packages for the project

## Machine learning models used:
1. Logistic FRegression
2. Random Forest
3. XGBoost

## How we detect fraud:
This project uses machine learning algorithms to detect credit card fraud. The dataset used in this project contains credit card transactions. It includes features such as transaction amount and several variables (V1 to V28). The target variable is the Class variable, which indicates whether a transaction is fraud or not.

The project uses three different machine learning models: logistic regression, random forest, and XGBoost. These models are trained on the dataset using the non-fraudulent transactions as the majority class and the fraudulent transactions as the minority class. The models are then evaluated on a test set, and various performance metrics such as accuracy, precision, recall, and F1 score are calculated.

In addition to the machine learning models, the project also includes EDA and visualizations.. These visualizations can help in understanding the data and identifying any patterns or relationships that may be useful in detecting fraud.


## Explanation for visualisations in the Code:
Count plot of class distributions: It shows that the dataset is highly imbalanced with a majority of non-fraudulent transactions and a small number of fraudulent transactions.

## Heatmap of correlation matrix: 
It shows the correlation between all the features in the dataset. Darker shades indicate stronger positive correlations, and lighter shades indicate weaker correlations or negative correlations. The heatmap can be useful to identify multicollinearity issues between features, which could impact the performance of some machine learning models.

![image](https://user-images.githubusercontent.com/68024510/235800545-b7ee38c0-562d-4af7-95ad-7159dc0aa86e.png)

Distribution plot of normalized amount:
It shows the distribution of the normalized amount feature after standard scaling. It helps visualize the spread of the feature values and identify any outliers or skewed distributions.

![image](https://user-images.githubusercontent.com/68024510/235802048-34ebd28c-d0f1-499f-bd51-ecfe30996c13.png)

Pair plot of select variables: 
It shows the pairwise scatter plots of select variables and the distribution of each variable. The hue parameter differentiates the plots for the two classes of transactions. The plot helps visualize the distribution of variables and how they differ between fraudulent and non-fraudulent transactions.

![image](https://user-images.githubusercontent.com/68024510/235802128-fa76bcdd-a174-4f27-b872-cf1598811c5d.png)

# Acknowledgments
Credit Card Fraud Detection dataset from Kaggle.
