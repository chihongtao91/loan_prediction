# Loan prediction
Predicting the risk of financial loans

## Objective
For financial institutions (e.g. banks, online lenders), a key task is to evaluate the risk and return of the loans given out. In this project, we will perform analysis on the publicly available loans dataset on Kaggle from Lending Club (https://www.kaggle.com/wendykan/lending-club-loan-data). 

The key question we are trying to answer is, given a loan application, will it turn out to be a good loans (fully paid), or a bad loan, which can be in any of these states (Default, Charged off, Late in payment). 

## Dataset
To run this project, first download the dataset: loan.csv from https://www.kaggle.com/wendykan/lending-club-loan-data, put it under below path:
```
data/loan.csv
```
For reference, we have included the Data Dictionary provided by lending club at this path: 
```
data/LCDataDictionary.xlsx
```

## Data Exploration, Pre-processing & Modelling
We have organised our code in two Jupyter notebook. 
* data_exploration.ipython 

This notebook covers the Explorative Data Analysis, for which we plot some of the useful data points according to domain knowledge. 

* data_preprocessing_modelling.ipython 

The second notebook entails the Data Pre-processing and Modelling, for which we tried various shallow classificiation models, as well as Deep Learning approach, with varying results. 

To run the notebooks, make sure you have the datasets (_loan.csv_) downloaded from the kaggle link stored in __./data__ directory, and you have jupyter notebook installed. Also below python packages need to be installed in your python environment:
* tensorflow
* sklearn
* pandas
* matplotlib
* seaborn

Then launch the jupyter server and click into the ipython notebook.
```
jupyter notebook
```
