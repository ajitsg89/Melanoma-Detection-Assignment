# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has 
the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents


## General Information
Multiclass classification model using a custom convolutional neural network in TensorFlow. 

### Algorithms Used

Convolutional Neural Network

### Dataset Information

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed by the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

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

## Results

### Image count in each class
![4](https://github.com/user-attachments/assets/de072265-ffd5-4899-a027-b3e24325d3b9)

### Baseline Model

Accuracy and Loss charts for the baseline model
![1](https://github.com/user-attachments/assets/b83923de-927c-492b-8c20-7ab0e1c686be)

### Augmented Model

Accuracy and Loss charts for the augmented model
![2](https://github.com/user-attachments/assets/3e51849d-e9b9-405e-bacb-aceac94c9eb2)

### Final Model

Accuracy and Loss charts for the final model

![3](https://github.com/user-attachments/assets/bd7b9815-bc43-4394-925d-5699e8a16bdc)


## Conclusions
As the accuracy of the model increases, the loss decreases. The final model has 93% train and 90% validation accuracy. The model is able to predict the class of the lesion with a high accuracy.
Augmenting the data and countering class imbalance helped in improving the accuracy of the model.


## Technologies Used
- Python
- Tensorflow
- Keras
- Augmentor
- Matplotlib
- NumPy


## Acknowledgements
- This project was inspired by UpGrad Team
- References if any: None
- This project was based on EDA, Machine Learning modules, CNN


## Contact
Created by [ajitgaikwad89@gmail.com] - feel free to contact me!
