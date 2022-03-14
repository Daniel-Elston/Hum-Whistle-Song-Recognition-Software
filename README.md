
<p align="center">
  
  ![ReadIm](https://user-images.githubusercontent.com/98388088/158096462-383949d5-f563-47d0-8118-5f06fe66498d.png)
  
</p>

<hr>

<p align="center">

  <a href="https://github.com/nsfw-filter/nsfw-filter/blob/master/LICENSE" target="_blank">
    <img alt="LICENSE" src="https://img.shields.io/github/license/navendu-pottekkat/nsfw-filter?style=flat-square&color=yellow">
  <a/>

</p>

# Hums and Whistle Song Recognition Software
  
<hr>



## Table of contents
- [Status and Details](#status-and-details)
- [Technology](#technology)
- [Introduction](#introduction)
    - [Project Description](#project-description)
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
- Date Coded: 01/11/22
- Link to raw Data: Offline Data Used. Some pickle files of transformed data are given. To aquire raw data, get N participants to hum or whistle to the tune of different songs N times.
- Notes: This is one of, if not, the first ML project I have under taken. Some errors or inefficiencies in code or text may exist. 


## Technology
- Language: Python 3.6.9
- Libraries: Pandas, Numpy, Sklearn


- Set up File: If complicated project with need to install many packages


## Introduction
The purpose of this project is ________. (Describe the main goals of the project and potential civic impact. Limit to a short paragraph, 3-6 Sentences)


### Project Description
Provide more detailed overview of the project. Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modeling work are you using to solve the problem? What blockers and challenges are you facing? Feel free to number or bullet point things here


### Objectives
What will this analysis/algorithm do/accomplish, keep it short


## Data Science Methodology

### Problem Formulation
Layman terms, short and to the point, relevant, specific, unambiguous and align with business strategy


### Data Engineering Methods
Uncovering structure from raw data EG transformation, Inferential Statistics, Machine Learning, Data Visualization, Predictive Modeling, etc.


### Modeling 
the process of creating a visual representation of either a whole information system or parts of it to communicate connections between data points and structures.


### Deployment
Application of model for predictions using transformed data


## Conclusions


## Contributing Members and Contacts
**Team Lead: [Daniel Elston](https://github.com/Daniel-Elston)**

|Name     |  GitHub Handles   |  
|---------|-----------------|
| xxx | [Full Name](https://github.com/[github handle])   |
| xxx | [Full Name](https://github.com/[github handle])   |

Please feel free to contact me if you have any questions, require any further information or wish to contribute.
Email 1: delstonds@outlook.com
Email 2: ec21024@qmul.ac.uk













# Hums and Whistle Song Recognition Algorithm
Users hum/whistle to the tune of a song, the algorithm attempts to identify the song name. A dataset of 747 .wav files were made available for the use of training and validating models. Although the raw data is too large to be uploaded to GitHub, the python pickle module was used to save the results of the data transformations. I have uploaded some of the pickle files (some pickle files still too large to upload) incase other want to analyse further. <br/>
<br/>
This repository includes a basic and advanced soltuion. I am currently too busy, but in the future I will upload the full datasets used and improve the solutions overall.

## Basic Solution:
The basic solution contains well known ways of feature engineering audio files. This uncovers structure (features) in the raw audio data. The features are then used to train classification models. 

## Advanced Solution:
The advanced solution required a creative problem solving. The aim was to advance the algorithm further. My advanced solution involves measuring the amount of 'silence' in each file. Although no new structures were determined from the raw data, my solution had the benefit of being able to be applied to various other data science processes/projects that dealt with background noise.


