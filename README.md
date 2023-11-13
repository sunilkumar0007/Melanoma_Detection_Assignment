# Project Name
- Melanoma Detection Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

Steps involved in this process: 
Data Reading/Data Understanding  
Dataset Creation
Dataset visualisation 
Model Building & training
Class distribution
Model Building & training on the rectified class imbalance data


## Conclusions
Training Accuracy:
The training accuracy remains constant at approximately 0.1337 for all epochs. This constant accuracy might indicate that the model is not effectively learning from the training data.

Validation Metrics:
The validation loss is consistently reported as 0.0000e+00, and the validation accuracy remains at 0.1151 for all epochs. This suggests that the model's performance on unseen validation data is not improving, indicating potential issues with generalization or the validation process. In summary, both the training and validation metrics show patterns that suggest the model is not effectively learning or generalizing from the provided data. Further investigation into the model architecture, loss function, and data characteristics may be needed to improve performance.

## Technologies Used
- tensorflow
- matplotlib
- numpy
- pandas



## Contact
Created by @sunilkumar0007  - feel free to contact me!

