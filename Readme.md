# Emotion Analysis from Image

This project aims to analyze the emotions of human beings from images. The project is still in progress and the accuracy of emotion prediction is not optimal at this stage.

## Data Preprocessing
Before training the model, we perform data preprocessing to prepare the image data for analysis.

## Data Augmentation
To increase the generalizability of the model, we apply data augmentation techniques to the image dataset.
 which includes zoom in and out rotation and some sort of image processing so that it can predict the emotion of a distorted rotated image also which were not there in the training set

## Convolutional Model
We have developed a convolutional model to classify the images into 7 different classes of emotions.
where we used batch normalization and dropout the layers as well.

## Model Training
During the training process, we apply various regularization techniques, such as plateau reducers, to improve the model's performance. We also record the progress at each step.

## Prediction

Please note that since this is the initial stage of the project, the accuracy of emotion prediction may not be satisfactory.for face detection we used the open cv and haarcascade frontface default file after detecting we sent the data (converted to the desired form) to prediction function to classify the images
