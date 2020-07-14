# Capstone - Car Color Classification Neural Network

### Executive Summary

A Convolutional Neural Network (CNN) model was trained as a color classifier for car photos. The model was built with Tensorflow and Keras and the image data was obtained from the Stanford Cars dataset. The objective of the model was to predict the RGB color based off an image of a car. The color categories was generated for each image based off of dominant RGB color and manhattan distance to closest existing RGB color. Images were augmented via ImageDataGenerator to better train the model. The model architecture was adapted from (Vehicle Color Recognition Using Convolutional Neural Network , Reza Fuad Rachmadi and I Ketut Eddy Purnama). 

The model was trained with 6108 images, validated with 2036 images, and predicted on 8041 images. There were 200 classes of colors determined in the training/validation set. The total number of parameters was 44,907,464. 

#### Background / Problem Statement

Cars and vehicles have unique car colors and are based off of pigmentation and luminosity. Automobile makers have specific paint color codes/names that usually have no alternative. This model can be used to convert a picture of a car to a reasonbly close RGB color. When an picture of a car is taken, the image is convereted to the RGB color scheme. This RGB color can be predicted with a properly trained CNN model. 


#### Model Architecture 

![Architecture](https://github.com/jasonqhuang/Capstone_JQH/blob/master/architecture.jpg)

### Conclusions/Recommendations

The model had a validation accuracy of 0.1650 which beat the baseline of 0.005. The model suffered from having far too many classes of colors available for predictions. Future steps will reduce classes and increase image augmentation. 

### Sources

Stanford Cars Dataset:https://ai.stanford.edu/~jkrause/cars/car_dataset.html
Vehicle Color Recognition Using Convolutional Neural Network , Reza Fuad Rachmadi and I Ketut Eddy Purnama: https://arxiv.org/pdf/1510.07391.pdf
Colors Dataset: https://github.com/codebrainz/color-names/blob/master/output/colors.csv