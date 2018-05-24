# Google Cloud and NCAA Machine Learning Competition

‘She Plays’ was conceived after developing an inclination towards Sports Analytics due to continuous discussions between the project team and the eventual realization of its deficiency in the field of Women sports games. 

The three main milestones in this project are - 

First, Data Acquisition, Munging and Exploration which involved collecting data records from the source Google Cloud NCAA ML competition. As the required attributes were spread across different files, integrating them into a consolidated dataset was an imperative task. This project involved identifying fields over which joining could be done efficiently. The Data exploration phase involved the derivation of useful and interesting relationship between the attributes, and thus, understanding the consolidated data.

Second, build a Predictive model based on historical data. This task involved the application of Machine learning concepts like Supervised Learning, Logistic Regression and Random Forest to build a predictive model. We built a variety of models using different combination of features. With the help of Regularization, Cross Validation and Feature Engineering, overfitting was avoided, and the model performance was improved.

Third, use the developed Predictive model for Prediction of 2018 championship results. The above created model is used to predict the probability that the team with lower id beats the team with higher id in each match. For example, if the tournament has 64 teams, then the model will predict (64*63)/2=2016 match ups. Here, if the team1 id is 3102 and team2 id is 4820, then the probability of team1 beating team2 in the match is predicted for the season 2018.

The project poster has been uploaded as Project_Poster.PDF.
The Technical details are available in the file ML_Report.PDF.

### Prerequisites and Getting Started

A DataBricks account to avoid separate installation of Python and Spark.

## Deployment
Upload each of the Databricks files and Run the files. 

# Built With

* [Databricks] - Code Development
* [PySpark] - Machine Learning Library 

## Authors

* Sanjana Rajagopala
* Shefali Vajramatti
* Sandya Madhavan
* Apoorva Rajendra Angre

## Acknowledgments

* Stack Overflow
* Professor Daniel Ernesto Acuna, Syracuse University.
