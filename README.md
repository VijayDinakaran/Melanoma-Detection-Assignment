# Melanoma detection using CNN
> In this assignment, I built a multiclass classification model using a custom convolutional neural network in TensorFlow. 
  

## Table of Contents
* [General Info](#general-information)
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to 
reduce a lot of manual effort needed in diagnosis.

* [Technologies Used](#technologies-used)
Pandas
Numpy
Tensorflow
Matplotlib

* [Conclusions](#conclusions)
Finally built a model that has validation accuracy of 86.93

* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths. 
The goal is to build a CNN based model which can accurately detect melanoma.

- What is the business probem that your project is trying to solve?
A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to 
reduce a lot of manual effort needed in diagnosis.

- What is the dataset that is being used?
Skin cancer ISIC The International Skin Imaging Collaboration

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


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
- Conclusion 1 from the analysis
Accuracy Improvement: Training accuracy started at 27.43% (Epoch 1) and steadily improved to 89.54% (Epoch 30). 
Validation accuracy started at 43.13% and reached a peak of 86.93% in Epoch 29, with a slight decline in the final epoch.

- Conclusion 2 from the analysis
Loss Metrics: Training loss decreased consistently from 1.90 to 0.27, showing that the model learned effectively during training. 
Validation loss followed a similar pattern, but there were some fluctuations. Validation loss hovered around 0.51.

- Conclusion 3 from the analysis
Overfitting or Underfitting: The gap between training accuracy and validation accuracy remained small throughout, indicating minimal overfitting. 
Training and validation losses did not diverge significantly, confirming the absence of overfitting. The model's steady improvement in both metrics suggests no underfitting.

- Conclusion 4 from the analysis
Impact of Class Rebalancing: Aftaer class rebalancing was applied (e.g., via data augmentation), the improvement in both accuracy and balanced validation metrics 
suggests it helped the model better generalize across imbalanced classes.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [https://github.com/VijayDinakaran] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
