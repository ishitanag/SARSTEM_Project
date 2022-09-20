# SARSTEM_Project

This project aims to tackle existing problems in speech emotion recognition (SER) by taking into account the acoustic cues and prosodic parameters to detect user 
emotion. Here, the work will be mainly on the Ryerson Audio-Visual Database (RAVDESS) to extract Mel Frequency Cepstral Coefficients (MFCC) from signals to 
recognise emotion. The librosa library will be used for processing and extracting audio files before testing and classification is carried out using 4 different 
classifiers for a comparative study. 

For a more comprehensive comparative analysis, we use the same dataset over 4 different classifiers namely Multi-layer Perceptron (MLP), Support Vector Machine (SVM), 
Decision Tree (DT) and Random Forest (RF) classifiers. Each classifier differs in some aspects and when applied to different datasets, their performance also varies. 

RAVDESS (Ryerson Audio-Visual Database of Emotional speech and song) has been used as the dataset which consists of 24 professional actors (12 male, 12 female) from 
Canada, in a neutral North American accent, vocalizing two lexically-related utterances. This dataset has been rated by 319 raters from the same region for testing the 
reliability and validation. The model has been evaluated for 4 different emotions: calm, happy, angry and disgust where calm and neutral are selected as threshold 
conditions. There are two levels of emotional intensity in each expression: normal and intense.
