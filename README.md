# Hums and Whistle Song Recognition Algorithm
Users hum/whistle to the tune of a song, the algorithm attempts to identify the song name. A dataset of 747 .wav files were made available for the use of training and validating models. Although the raw data is too large to be uploaded to GitHub, the python pickle module was used to save the results of the data transformations. I have uploaded some of the pickle files (some pickle files still too large to upload) incase other want to analyse further. <br/>
<br/>
This repository includes a basic and advanced soltuion. I am currently too busy, but in the future I will upload the full datasets used and improve the solutions overall.

## Basic Solution:
The basic solution contains well known ways of feature engineering audio files. This uncovers structure (features) in the raw audio data. The features are then used to train classification models. 

## Advanced Solution:
The advanced solution required a creative problem solving. The aim was to advance the algorithm further. My advanced solution involves measuring the amount of 'silence' in each file. Although no new structures were determined from the raw data, my solution had the benefit of being able to be applied to various other data science processes/projects that dealt with background noise.


