# The Data
LendingClub is a financial services company located in San Franscisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market.

## The Goal
The goal of this project is to create a model that would predict a whether a borrower will pay back their loan or be charged off using the historical data on loans. In this way, the model can predict future potential customers and assess whether they pay back their loan or not.

## Project Structure
- 'lending_club_loan_two.csv': This file contains the train and testing data.
- 'lending_club_info.csv': This file contains the features info.
- 'LendingClassification.ipynb': This file contains the whole machine learning process from data cleaning to model deployment.
- 'sample_prediction/': This directory contains a sample prediction process of this model.
- 'prediction/': This directory contains the model, data processing script, and prediction script.

## Usage
To predict future data with the same features of this data set, follow the steps:
1. Clone this repository: https://github.com/pvinsevi/LendingClassification.git
2. Put your data in prediction folder or make sure your dataset is in the same directory as the files in the prediction folder.
3. Rename your dataset filename to "raw_data.csv".
4. Run "data_manipulation.ipynb" using a jupyter notebook.
5. Wait until "data.csv" shows.
6. Run "script_predict.ipynb" script using a jupyter notebook.
7. Your data will be ready with predictions in "predicted_data.csv" file.

