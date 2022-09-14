# CNN based model to accurately detect melanoma
> To build a CNN based model to accurately predict the presence of melanoma and alert dermatologists


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. 
- It accounts for 75% of skin cancer deaths. 
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
- All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following diseases:

      -Actinic keratosis
      -Basal cell carcinoma
      -Dermatofibroma
      -Melanoma
      -Nevus
      -Pigmented benign keratosis
      -Seborrheic keratosis
      -Squamous cell carcinoma
      -Vascular lesion


## Conclusions
- Developing the model with the given data may end up model with overfitting and biased due to class imbalance 
- Overfitting can be reduced by using dropout
- Class imbalance will reduce the accuracy of the developed model, resulting in biased output 
- Model that can perform well in training dataset and validation set can be created with dropout after handling the class imbalance 


## Technologies Used
- Google drive
- Python 
- Keras 
- CNN
- BatchNormalization
- Dropout 


## Contact
Created by Diwakar S - feel free to contact me!
