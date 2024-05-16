# Predictive-Modeling-in-Sports-Betting
Introduction
In this research, we concentrate on predicting soccer match outcomes and evaluating relationships between performance metrics and game results by utilizing a comprehensive dataset from Football-Data (https://www.football-data.co.uk/data.php). It contains basic information about the match and pre-match betting odds. The dataset consists of 20,901 games with 21 variables.

Our objectives include developing a predictive model that integrates a variety of data points to forecast match outcomes, identifying the most significant factors determining match results, and comparing the effectiveness of different statistical and machine learning methods in sports outcome predictions.

Contents
Predictive-Modeling-in-Sports-Betting/

src/          # Source code
eda_soccerdata.R                     # Exploratory data analysis
final_code.R                               # Main code
get_Football_Data.ipynb          # Get data from Football Data (main)
get_Soccer_API_data.ipynb          # Get data from Soccer API
soccer_models.R                       #Code for first report
data/                # Static files
soccerdata.csv           # Final CSV file for the models
Soccer Data/               # Folder of CSV files for each league season (input for get_Football_Data.ipynb)
docs/
Presentation.pdf
Report.pdf
README.md
Basic Usage
Run the get_Football_Data.ipynb file to get the data
Run the eda_soccerdata.R to perform exploratory data analysis on the dataset
Run final_code.R to get the output of the models
Output
The code produces these statistics in its output:

Logistic Regression for the likelihood of a home win (0 = Win, 1 = Lose)
Random Forest for the likelihood of a home win
Simplified Logistic Regression for the likelihood of a home win
Accuracy, AUC-ROC, precision, recall, F1 score, and CV accuracy for each model
