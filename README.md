# AICUP_2023_Spring_acoustics
>Repository for 2023 AI CUP acoustics competition.

## Leaderboard
|Public Rank|Public Score|Private Rank|Private Score|
|--|--|--|--|
|6 / 371|0.659922|28 / 371|0.558209|

## Enviroment
Setup enviroment:  
```
conda env create -n ~~~
conda activate ~~~
```
## Packages: 
```
pip install librosa
pip install pandas
pip install torch
pip install sklearn
```
## Model
- ```1_AI_CUP_mfcc_??.ipynb```: Models trained with different parameter ```n_mfcc```.  
- ```2_ensemble.ipynb```: Use ensemble method to combine the predictions of five models.

## Data
- ```mfcc_??.pth```: Weights of each model.  
- ```pub_pri_mfcc_??.csv```: Predictions of each model.  
- ```ensemble.csv```: The final result after ensemble.

## Reproducing submission
1. Run ```1_AI_CUP_mfcc_??.ipynb``` without training part.
2. Run ```2_ensemble.ipynb```
