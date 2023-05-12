# Simple Machine Learning Project Lending Classification 
This repository contains a simple machine learning project that predicts if a borrower will pay the loan or be charged-off.

## Project Structure
- 'lending_club_loan_two.csv': This file contains the train and testing data.
- 'lending_club_info.csv': This file contains the features info.
- 'LendingClassification.ipynb': This file contains the whole machine learning process from data cleaning to model deployment.
- 'sample_prediction/': This directory contains a sample prediction process of this model.
- 'prediction/': This directory contains the model, data processing script, and prediction script.

## Usage
To predict future data with the same features of this data set, follow the steps:
1. Download the prediction folder.
2. Put your data in prediction folder or make sure your dataset is in the same directory as the files in the prediction folder.
3. Rename your dataset filename to "raw_data.csv".
4. Run "data_manipulation.ipynb" using a jupyter notebook.
5. Wait until "data.csv" shows.
6. Run "script_predict.ipynb" script using a jupyter notebook.
7. Your data will be ready with predictions in "predicted_data.csv" file.

