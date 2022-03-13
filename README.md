# Hums-and-Whistle-Song-Detection-Algorithm
Users hum/whistle to the tune of a song, the algorithm attempts to identify the song name. A dataset of 747 .wav files were made available for the use of training and validating models. Although the raw data is too large to be uploaded to GitHub, the python pickle module was used to save the results of the data transformations.<br/>
<br/>
This repository therefore includes a basic solution, an advanced soltuion and a pickle solution. 

## Basic Solution:
The basic solution contains well known ways of feature engineering audio files. This uncovers structure (features) in the raw audio data. The features are then used to train classification models. 

## Advanced Solution:
The advanced solution required a creative solution to uncovering structure in the raw data. My advanced solution involves measuring the amount of 'silence' in each file. Although no new structures were determined from the raw data, my solution had the benefit of being able to be applied to various other data science processes that dealt with background noise.

## Pickle Solution:
The pickle solution is simply a combination of the previous two solutions (basic and advanced), but it can be performed on GitHub



