
<p align="center">
  
  ![ReadIm](https://user-images.githubusercontent.com/98388088/158096462-383949d5-f563-47d0-8118-5f06fe66498d.png)
  
</p>

<hr>

<p align="center">

  <a href="https://github.com/nsfw-filter/nsfw-filter/blob/master/LICENSE" target="_blank">
    <img alt="LICENSE" src="https://img.shields.io/github/license/navendu-pottekkat/nsfw-filter?style=flat-square&color=yellow">
  <a/>

</p>

<h1 align='center'> Hums and Whistle Song Recognition Software </h1>
  
<hr>



## Table of contents
- [Status and Details](#status-and-details)
- [Technology](#technology)
- [Introduction](#introduction)
    - [Project Description](#project-description)
    - [Basic Solution](#basic-solution)
    - [Advanced Solution](#advanced-solution)
    - [Objectives](#objectives)
- [Data Science Methodology](#data-science-methodology)
    - [Problem Formulation](#problem-formulation)
    - [Data Engineering Methods](#data-engineering-methods)
    - [Modeling](#modeling)
    - [Deployment](#deployment)
- [Conclusions](#conclusions)
- [Contributing Members and Contacts](#contributing-members-and-contacts)


## Status and Details
- Project Status: [Completed]
- Date Coded: 01/11/21
- Link to raw Data: Offline Data Used. Some pickle files of transformed data are given. To aquire raw data, get N participants to hum or whistle to the tune of different songs N times.
- Notes: This is one of, if not, the first ML project I have under taken. Some errors or inefficiencies in code or text may exist. 


## Technology
- Language: Python 3.6.9
- Libraries: Pandas, Numpy, Sklearn, matplotlib, seaborn, Librosa, soundfile, math, xgboost, os, sys, re, pickle, glob, IPython, urllib, zipfile
- Sep up File: N/A
- Pickle: Pickle files containing saved results of feature extraction have been provided


## Introduction
The purpose of this project is to allow a user the ability to find a song name by humming or whistling the tune. Apps such as Shazam allow for a user to identify a song when already listening to it. However if you are currently no longer listening, this algorithm can give you a chance of identifying the song name.


### Project Description
The dataset used for this project was made by students at the Queen Mary University of London. Each student provided 28 .wav files of hums or whistles to a list of different songs. Around 200 students took part, resulting in a dataset that was varied and highly representative of the enviroment of deployment. The raw data was close to perfect for model training. Some data was kept private by the University. The dataset available in this project was a total of 747 .wav files.

Feature extraction takes place to uncover data structure in the .wav files. This results in features that are able to be analysed and used for model training. Classification models were trained and validated using the processed dataset. A model of accuracy 89% was determined however the validation accuracy suggests under fitting.


### Basic Solution:
The basic solution contains well known ways of feature engineering audio files. This uncovers structure (features) in the raw audio data. The features are then used to train classification models. 

### Advanced Solution:
The advanced solution required a creative problem solving. The aim was to advance the algorithm further. My advanced solution involves measuring the amount of 'silence' in each file. Although no new structures were determined from the raw data, my solution had the benefit of being able to be applied to various other data science processes/projects that dealt with background noise.


### Objectives
- Perform feature extraction of raw .wav file data
- Train and validate machine learning models
- Identify song name from user input humming or whistling to song tune
- Provide model metrics and analyse results


## Data Science Methodology

### Problem Formulation
Often times a song can get stuck in your head, or you really enjoy listening to a song on the radio but you cant use Shazam as your driving. This algorithm provides a means to identify a song based on you, the user, inputting the data yourself via humming or whistling to the tune.


### Data Engineering Methods
- Data Transformation
- Data Preprocessing
- Inferential Statistics
- Data Visualisation
- Machine Learning
- Predictive Modelling
- Model metric analysis


### Modeling 
The preprocessed data underwent dimensionality reduction through the use of principle component analysis. The dataset split into test and validation sets. The model was trained and validated using a variety of classifiers. The XGB classifier was deemed the most well suited for the needs of this analysis. The model had the highest training and validation accuracy with relatively low signs of under fitting.


### Deployment
The objective of this project was to train and validate a model. Deployment was not required.


## Conclusions
A training accuracy of 89% and validation accuracy of 61% was observed. The XGB classifier was used and showed great confusion for the validation dataset. The features extracted were likely not useful enough for the model to differentiate between songs. Therefore, deployment of this model is not advised until further feature extraction takes place.


## Basic Solution:
The basic solution contains well known ways of feature engineering audio files. This uncovers structure (features) in the raw audio data. The features are then used to train classification models. 

## Advanced Solution:
The advanced solution required a creative problem solving. The aim was to advance the algorithm further. My advanced solution involves measuring the amount of 'silence' in each file. Although no new structures were determined from the raw data, my solution had the benefit of being able to be applied to various other data science processes/projects that dealt with background noise.

## Contributing Members and Contacts
**Team Lead: [Daniel Elston](https://github.com/Daniel-Elston)**

|Name     |  GitHub Handles   |  
|---------|-----------------|
| Daniel Elston | [Git DE](https://github.com/Daniel-Elston)   |

Please feel free to contact me if you have any questions, require any further information or wish to contribute.<br/>
Email 1: delstonds@outlook.com<br/>
Email 2: ec21024@qmul.ac.uk
