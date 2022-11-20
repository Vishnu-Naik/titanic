# Titanic Challenge from Kaggle

## About project
This project is a solution I submitted for kaggle's beginner's machine learning challenge.
This challenge is about the infamous titanic wrekage and here we are trying to predict the chances of an individual's survival.

## Folder structure
This repo has multiple folder and files, here are the details of what each folder and files mean

### Data:

This folder has data that was given by kaggle in order to solve this challenge.

* _train.csv_: a csv file which is used for training the model
* _test.csv_: a csv file which is used for testing the model and submitting the results obtained as a solution.
* _typical_format_gender_submission.csv_: this csv file is a typical file in which the submission should be formatted.

### Results:

This folder contains the final result of the trained model on test data, this file was submitted to kaggle as a part of solution.

### ipynb files:

&emsp; There are multiple jupyter notebooks in this repo, where I tried various appoaches or should I say experimentation. 
I tried to learn alot of concepts like multiple input model with diverse datatype features, similar datatype features.

Here I'll give a high level knowledge about each file and what I tried in each file.

* _multi-input-only-predict.ipynb_ :

&emsp; Here I dint try anything special just took all the featues and fed into the model.

* _multi-input-uniform-datatype.ipynb_ :

&emsp; Here I converted all the featues to a single datatype.

* _multi-input-diverse-datatype.ipynb_ :

&emsp; Here I tried to include different type of data types.

* _multi-input-relevant-datatype.ipynb_ :

&emsp; This is the final model which was used to solve the challange where I am using only features which makes sense for prediction.
