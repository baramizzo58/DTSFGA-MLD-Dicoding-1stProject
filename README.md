# DTSFGA2022-MLD-Dicoding-Beginner-FinalProject
Final Project of Machine Learning Developer (Learn Machine Learning for Beginners Stage) Training in Fresh Graduate Academy Program (Digital Talent Scholarship 2022).

## Project explanation
Making Picture Classification - Rock Paper Scissors case study. This algorithm will identify the picture uploaded as Rock, Paper, or Scissors.

## Dataset
Dataset is downloaded from https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip

## Pre-Processing Data
* Using `ImageDataGenerator`

## Modelling
* Using model architecture with CNN
* Model is compiled with `categorical_crossentropy` loss function, `adam` optimizer, and using `accuracy` metrics
* Using callbacks with 96% accuracy

## Result:
* Epoch: 16/20
* loss: 0.1132
* accuracy: 0.9610
* val_loss: 0.1807
* val_accuracy: 0.9750
