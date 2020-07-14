# Capstone - Car Color Classification Neural Network

### Executive Summary

A Convolutional Neural Network (CNN) model was trained as a color classifier for car photos. The model was built with Tensorflow and Keras and the image data was obtained from the Stanford Cars dataset. The objective of the model was to predict the RGB color based off an image of a car. The color categories was generated for each image based off of dominant RGB color and manhattan distance to closest existing RGB color. Images were augmented via ImageDataGenerator to better train the model. The model architecture was adapted from (Vehicle Color Recognition Using Convolutional Neural Network , Reza Fuad Rachmadi and I Ketut Eddy Purnama). 

The model was trained with 6108 images, validated with 2036 images, and predicted on 8041

#### Background

Whiskey and Whisky are two ways to refer to the popular liquor. The respective subreddits hold multiple daily posts referrring to the drinks. 

#### Problem Statement

How well does a model perform at determining if a post came from the bourbon or scotch subreddits?

#### Model Architecture 

![Architecture](https://github.com/jasonqhuang/Capstone_JQH/blob/master/architecture.jpg)

### Conclusions/Recommendations

The model performed very well with a score of 84.5% and accuracy of 84.5%. This can be attributed to very specific words making it easy to determine original subreddit. To improve the model, adding comments and searching for flavor profile text can improve the complexity of the model. 

### Sources

Stanford Cars Dataset:https://ai.stanford.edu/~jkrause/cars/car_dataset.html
Vehicle Color Recognition Using Convolutional Neural Network , Reza Fuad Rachmadi and I Ketut Eddy Purnama: https://arxiv.org/pdf/1510.07391.pdf
Colors Dataset: https://github.com/codebrainz/color-names/blob/master/output/colors.csv