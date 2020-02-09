# PetFinder.my Adoption Prediction

The propuse of this this project was to predict if animals (dogs or cats) would be adopted or not, according to their characteristics.

You can find the project page here : https://www.kaggle.com/c/petfinder-adoption-prediction

## Description

This project was developed in the context of a machine learning course in University of Lisbon.

The project had three main tasks:

	-> Exploratory data analysis;
	-> A binary classification task, to predict whether the animal would be adopted or not;
	-> A multi classification task to predict about the five classes.
	
For each of tasks, four types of machine learning models were trained: Rule models, distance based models, tree models and probablistic models.

The machine learning pipeline applied was:

	1. Feature Engineering: binning techniques were applied to some features;
	2. Resampling techniques were applied because the targets was unbalanced;
	3. Feature selection: random forest to select the best features;
	4. GridSearchCV for hyper parameters tunning;
	5. Tested different combinations of features.
	
The results of the all the models tested are saved in the results folder. 

### Prerequisites

Anaconda and imbalanced-learn

### Structure

Jupyter notebook project.ipnyb with all the python code

data folder with the csvs

results folder, used to save the results of the tested models