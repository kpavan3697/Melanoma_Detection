# Melanoma_Detection

> Build CNN model to melanoma skin cancer based on skin images.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project is part of an assignment for an Advanced Certification Program in Machine Learning and Deep Learning (ACP in ML & DL) offered by IIIT Bangalore. The objective is to develop a custom convolutional neural network (CNN) using TensorFlow for multi-class classification.

- The primary aim of the project is to construct a CNN model capable of accurately detecting melanoma, a potentially fatal form of skin cancer. Melanoma accounts for 75% of skin cancer-related deaths and early detection is crucial for effective treatment. By automating the evaluation of images and alerting dermatologists to the presence of melanoma, this solution has the potential to significantly reduce the manual effort required for diagnosis.

- The dataset comprises 2,357 images depicting various malignant and benign oncological conditions, sourced from the International Skin Imaging Collaboration (ISIC). These images have been categorized based on ISIC's classification system, ensuring an equal distribution among subsets with the exception of melanomas and moles, which are slightly overrepresented.


The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

The following steps were undertaken:

- Formulated training and validation datasets from the training directory, utilizing a batch size of 32 and resizing images to 180x180 pixels.
- Developed the initial CNN model and trained it for approximately 20 epochs, identifying overfitting.
- Implemented image augmentation techniques to enhance dataset variability and incorporated dropout layers to mitigate overfitting. Despite these efforts, both training and validation accuracies remained low, indicating potential underfitting.
- Conducted an assessment for class imbalance, revealing disparities in the number of samples across different classes. To address this, the dataset was augmented by introducing 500 new images for each class.
- Trained the final model for around 20 epochs using the augmented dataset, resulting in improved accuracies and no signs of underfitting.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Data augmentation, class imbalance handling and adding dropout layers greatly improved model performance.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter Notebook - version 6.5.4
- Python - version 3.11.5
- numpy - version 1.24.3
- pandas - version 2.0.3
- seaborn - version 0.12.2
- matplotlib - version 3.7.2
- Keras - version 3.1.1 
- Tensorflow - version 2.16.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
<!-- Give credit here. -->
- This project is done with reference to a example (CIFAR-10 Classification with Python) covered in the Advanced Regression module.


## Contact
Created by [@kpavan3697] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
