# NYPD_Analysis-ML

## NYPD Civilian Complaints Data
This project contains data on 12,000 civilian complaints filed against New York City police officers. 
The data and its corresponding data dictionary in this repo is downloadable here: https://www.propublica.org/datastore/dataset/civilian-complaints-against-new-york-city-police-officers

## Introduction
In this repo, I attempt to understand systemic biases in gender and racial policing. After conducting exploratory data analyses with this data, I conducted some hypothesis testing and identified a prediction problem for which to train a sklearn ML model.

## Hypothesis Testing
The question I decided to investigate for the hypothesis test is: are female complainants more likely to recieve an 'Arrest - other violation/crime' outcome for the same nypd contact reasons as males?

## Classification Model
The prediction problem I am attempting is a classification problem. I aim to build and finetune a sklearn DecisionTreeClassifier model to predict whether the mos_ethnicity of an NYPD officer is White or Not White. 
