# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


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



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model building with epoch 20 on current dataset without modification shows slight overfiting.  
- Data augmentation strategy with epoch 20 indicate overfiting with new data.
- With class imbalance using sample data on rotation model along with normalization dropout it is overfiting with training dataset.
- Without normalization and with dropout can see the model is performing well and achieve high accuracy. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow: 2.18.0
- PIL: 11.0.0
- keras: 3.6.0
- Augmentor: 0.2.12

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@ritesh9835] - feel free to contact me!