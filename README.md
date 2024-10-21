# Readme file
# Title: Exploration of classifer models using bank marketing data from a Portugese bank

## Description
### In this project, we used data collected from UCI repository, this data represents a marketing campaign by a Portugese bank
### For this project, we explored the dataset using visualization, and then prepared the data for modeling, tried and evaluated different classifier models
#### Logistic Regression
#### KN Neighbors Classifier
#### Decision Tree Classifier
#### SVM Classifier

### We first evaluated the performance of the classifier models using default parameters
### We then developed optimal classifier models using a two step approach 
#### Reducing the feature set to around 20 features
#### Determine the optimal hyperparameters that optimized "auc_roc" metric

## Installation

### The project in the repository will include the following files
#### Readme file: Readme.md
#### Jupyter Notebook: Module17_ClassifierAssessment
#### Data file: bank-additional.csv

### Create a project directory and loading the Jupyter notebook
#### Download Module17_ClassifierAssessment file on to the project directory
#### Upload file onto the Jupyter Notebook and open it

### Data set up: 
#### Create the directory data/ under the root directory of Jupypter Notebook
#### Save the bank-additional.csv file under this directory


## Usage
#### After setting up the data, you can run the Python code in the Jupyter notebook 
#### The code has markdown sections that outline the approach of the analysis and can help you understand the logic
#### Upon running the code, you will generate string outputs and plotly

## Data
### This data comes to us from UCI with about 4119 customer contact records for a Portugese bank marketing campaign to sell a savings deposit product (this is a smaller dataset, UCI repository has the complete dataset with over 40K records)
### The data contains the following
#### Details of bank customer
#### Tele marketing details (type of contact, timing of contact) 
#### Details about  prior marketing campaign efforts with the customer
#### Macro economic indicators
#### Outcome of the marketing outreach - whether the customer bought the product or not


## Contribution
### You can extend and refine the model by exploring the following
#### Leveraging the "complete dataset" consisting of over 41K records if you have access to higher computing power
#### Conduct additional feature engineering, to combine certain features (such as month, day of the week)
#### You can explore further optimizing the classifier models by exploring additional hyperparamters
### You can save the visualization plots as png files 

