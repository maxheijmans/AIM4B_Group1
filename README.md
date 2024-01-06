# DBM_Group1
# Project Overview

This repository contains two main folders: `BankTransactions` and `UsedCarAuctionPrices`, each dedicated to distinct data analysis and modelling tasks.

## BankTransactions Folder

### Contents:
- `bank_transaction.csv`: Dataset file containing banking transaction information.
- `EDA_Clustering.ipynb`: Jupyter Notebook file with Exploratory Data Analysis (EDA) and clustering processes.

### Tasks Accomplished:
1. **Exploratory Data Analysis and Data Cleaning**:
   - Conducted data cleaning and exploratory analysis using techniques similar to prior datasets.
   
2. **Feature Engineering**:
   - Implemented feature engineering based on the insights gained from the EDA step.

3. **Dimensionality Reduction**:
   - Utilised Principal Component Analysis (PCA) for dimensionality reduction.

4. **Clustering**:
   - Applied K-means clustering on the PCA results to find optimal parameters using techniques like the elbow method for k-value selection.
   
5. **Cluster Interpretation**:
   - Investigated resulting clusters by plotting original features for each cluster to draw conclusions and answer business questions.
   
6. **Bonus Task**:
   - Compared K-means clustering with (H)-DBSCAN method to determine better performance for the business question.

## UsedCarAuctionPrices Folder

### Contents:
- `car_prices.csv`: Dataset file containing used car auction prices.
- `EDA.ipynb`: Jupyter Notebook file focusing on Exploratory Data Analysis and data cleaning.
- `Modelling.ipynb`: Jupyter Notebook file concentrating on model training and evaluation.
- `feather_dataset`: Dataset connecting EDA and modelling stages.

### Tasks Accomplished:
1. **Exploratory Data Analysis and Data Cleaning**:
   - Conducted data cleaning, descriptive statistics, outlier removal, and missing value imputation based on statistical techniques.
   
2. **Feature Engineering**:
   - Created a feature dataset from clean data including feature scaling, selection, categorical variable encoding, and new feature generation.
   
3. **Datasets Generation**:
   - Produced train, validation, and test datasets as per lecture/lab instructions.

4. **Model Fitting**:
   - Performed model fitting, hyperparameter tuning (using grid search), and visualized neural network training progress.
   
5. **Model Evaluation**:
   - Evaluated model fit using appropriate performance metrics and produced visualizations to showcase accuracy on the test set.

6. **Model Selection**:
   - Compared performance between neural network and random forest models to identify the better one.

7. **Explainability**:
   - Explained predictions of the best model based on feature importance methods discussed in lectures.

8. **Bonus Tasks**:
   - Fit additional models (linear/logistic regression, KNN, XGBoost) to compare with RF and neural network.
   - Implemented 5-fold cross-validation for random forest model hyperparameter optimization.

Feel free to explore each folder for detailed code implementation and analysis.