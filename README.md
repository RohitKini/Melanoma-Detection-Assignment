# Project Name

This project aims to build a Convolutional Neural Network (CNN) model for the accurate detection of Melanoma, a dangerous type of skin cancer.  The model will be trained on a dataset of 2357 images of various skin cancer types. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- **Background:** Melanoma is a deadly form of skin cancer, accounting for 75% of skin cancer deaths.  Early detection is crucial for successful treatment.   

- **Business Problem:** The project addresses the need for an automated solution to assist dermatologists in identifying Melanoma from skin images, reducing manual effort and potential errors in diagnosis.   

- **Dataset:** The dataset comprises 2357 images categorized into 9 sub-directories, each representing a different skin cancer type.

## Conclusions
- **Overfitting:** Initial model training showed signs of overfitting, with higher accuracy on training data than validation data.    

- **Data Augmentation:** Data augmentation techniques were applied to mitigate overfitting.
  
- **Underfitting:** After data augmentation, the model exhibited underfitting, failing to learn effectively.

- **Class Imbalance:** Analysis revealed class imbalance in the dataset, which could contribute to the model's performance issues.    

- **Addressing Imbalance:** The Augmentor library was used to balance the dataset by adding more samples to under-represented classes.   

- **Final Model:** The final model was trained on the balanced dataset, achieving improved performance. 

## Technologies Used
- Python 3.11
- TensorFlow
- Keras
- Matplotlib
- NumPy
- Pandas
- Augmentor

## Acknowledgements

- The project was based on a CNN assignment.
- The Augmentor library was instrumental in addressing class imbalance.


## Contact
Created by [[@RohitKini](https://github.com/RohitKini)] - feel free to contact me!
