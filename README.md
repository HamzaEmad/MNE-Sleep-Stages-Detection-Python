# MNE-Sleep-Stages-Detection-Python

# Description:
The steps to classify any signals dataset are as follows:- 
1. Preprocess signals 
2. Divide data into epochs of equal sizes
3. Feature Engineering on the epochs
4. Train Classification Model 

We engineered different features from the epochs data. The features are able to distinquish between the 5 sleep stages to train the model. 

* We have extracted the features from time domain or frequency domain

Your epochs dataset is of shape `(714, 7, 3000)` where the dimensions represent `number_of_epochs*number_of_channels*number_of_samples`

The output shape is `number_of_epochs*length_of_feature_vector`. If your 3 features contain 2 values each, then the output should be of shape `(714, 6)` where `length_of_feature_vector = 3 * 2`. 

Note that the features don't have to be of the same length.
