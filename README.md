# Emotion Recognition using Speech using Librosa library and MLPClassifier


## Overview:
The project deals with understanding emotional state of a human by extracting/detecting the features conveyed through their speech/voice. 

## Introduction:
Emotions plays an important role in daily **interpersonal** human interactions. This is essential for our rational as well as intelligent decisions.

Also, detecting emotions is one of the most important **marketing** strategies in today's world as most of the daily decisions of the humans are driven by their emotional state at that moment.

As a result, this type of application has much **potential** in the world that would **benefit** companies and start-ups and also even provide safety to consumers.

## Components
Traditional Speech Emotion Recognition system undergoes the following **phases** to map speech signals into emotions:
### 1. Speech: 
It is given as input (from which emotions are to be extracted)
### 2. Pre-processing:
The removal of unwanted noise signals from the speech to extract high frequency speech signals.
### 3. Feature Extraction:
Extarcting the desirable features from the pre-processed speech to identify the human emotions.
### 4. Classification:
Now, after extracting the features we have to map the features to the corresponding emotions using the classifiers.
Some of the traditional classifier are:
GMM (Gaussian Mixture Model), ANN (Artificial Neural Network), SVM (Support Vector Machine), etc.
For more accurate predictions Deep Learning Models are preferred namely:
CNN (Convolutional Neural Networks), etc.
### 5. Emotion:
It is the output which we want to obtain after training our raw data (i.e., in the form of "utterance") over a suitable classifier.

## Technology Used:
### - Python
### Python Libraries Used:
- **Librosa:** It is used for analyzing audio and music
- **scikit-learn:** It is a very robust library in ML and statistical modelling applications including classifications, regression, clustering, etc.
- **Numpy:** It is used when working with numerical data (specifically; single or multi-dimensional arrays)
- **soundfile:** It is used for reading and writing sound/audio files

## Dataset:
### RAVDESS (Ryerson Audio & Visual Database of Emotional Speech and Song)
 - The RAVDESS is a multi-modal database of emotional speech and song. The database is gender balanced consisting of 24 professional actor, vocalizing lexically matched statements in a neutral North American accent.
 - Speech emotions includes: calm, happy, sad, angry, fearful, surprise, and disgust expressions.
 - Each expression is produced at 2 levels of emotional intensity (normal and strong) with an additional neutral expression.
 - Speech audio-only files are of 16bit, 48kHz .wav format. Full dataset is of 24.8 GB.
 - **Kaggle's RAVDESS dataset contains 1440 file: 60 trails per actor x 24 actors = 1440**
 - [Kaggle's audio and speech dataset](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio/download)
