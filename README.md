# Pneumonia-Detection-using-VGG16
DL project using Pneumonia dataset available on Kaggle.

## About the Architecture
Pre-trained weights were used from the imagenet task.
All layers of VGG16 were pre-trained
A Flatten layer followed by a dense layer, and the final output dense layer was added.
Number of classes : 2 (Normal-0 and Pneumonia-1)

## Preprocessing
All input images to the NN were set to [224,224,3]
ImageDataGenerator from keras was used to rescale/resize all images

## Compiling Model
Epochs run - 3
Steps per Epoch - 51
Final Accuracy attained -  
Final Loss during validation - 

## About Dataset
Source - https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
The dataset is balanced
4894 images used in the training
624 images used for testing
One image (Pneumonia) was added to test the saved model.h5
