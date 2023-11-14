# Melanoma Detection using CNN Model
This is CNN Model prepared for Detection of  melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Information]
* [Conclusions]
* [Technologies Used]
* [Acknowledgements]
* [Contact]


## General Information
- This is CNN Model prepared for accurate Detection of  melanoma.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
   All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
-  The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- While creating inital model the model seems to be overfitting
- After using augumentaion, overfitting was gone, but due to class imbalance model was underfitting
- After resolving class imbalance using Augmentor, the model seems to be working fine with Train accuracy as 90%, validation accuracy 75% and test accuracy as 98%
  


## Technologies Used
- Python 3.10.9
- matplotlib 3.7.0
- seaborn 0.12.2
- sklearn 1.2.1
- statsmodels 0.13.5


## Acknowledgements
- This project was inspired UPGRAD learning platform
- References : https://learn.upgrad.com/course/4616/segment/42428/247790/756788/3806654
- This project was based on https://learn.upgrad.com/course/4616/segment/42428/247790/756788/3806654


## Contact
Created by https://github.com/KavitaGupta2023 


