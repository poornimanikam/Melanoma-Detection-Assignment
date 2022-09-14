# Melanoma-Detection-Assignment

>To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths.
A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC)
-The data set contains the following diseases:
    Actinic keratosis
    Basal cell carcinoma
    Dermatofibroma
    Melanoma
    Nevus
    Pigmented benign keratosis
    Seborrheic keratosis
    Squamous cell carcinoma
    Vascular lesion
- We are building a model that can evaluate images and alert dermatologists about the presence of melanoma.
It has the potential to reduce a lot of manual effort needed in diagnosis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- First model is overfitting because we can also see difference in loss functions in training & test around the 10-11th epoch. 
- Second model build has no improvement in accuracy but we can definitely see the overfitting problem has solved due to data augmentation.
- Final Model is still overfitting.
   Training Accuracy has increased by using Augmentor.
   The problem of overfitting can be solved by adding dropout layers or add more layer.
    The Model can be further improved by tuning the hyperparameters

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pathlib
- tensorflow
- matplotlib
-os
-PIL
-Pandas
-Numpy


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by @poornimanikam - feel free to contact me!



<!-- You don't have to include all sections - just the one's relevant to your project -->
