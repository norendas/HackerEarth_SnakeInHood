# HackerEarth_SnakeInHood
Identify the snake breed
https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-snake-breed-detection/machine-learning/identify-the-snake-breed-5-66d9a9f5/

## Problem statement
You have been hired as a Deep Learning engineer to create a sophisticated model that can detect the breed of a snake from its image.

## Data description

This data set consists of the following two columns:
Column Name 	Description
image_id 	Name of the image file
breed 		Snake breed [35 different breeds]

The data folder consists of two folders and two .csv files. The details are as follows:
train: Contains 5508 images for 35 classes 
test: Contains 2361 images
train.csv: 5508 x 2
test.csv: 2361 x 1


The training data images are highly skewed / imbalance:

1) use training weight for each class.
2) use image augmentation to create new augmented images to balance all classes.
3) use stratified K-Fold split to make train and validation set.



