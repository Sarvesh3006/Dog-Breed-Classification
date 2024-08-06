# Dog-Breed-Classification
Download the data from kaggle [link for downloading](https://www.kaggle.com/c/dog-breed-identification-data/overview)
This project focuses on classifying dog breeds using a Convolutional Neural Network (CNN) model. The dataset used contains images of dogs belonging to 120 different breeds.

## Table of Contents
* Installation
* Dataset
* Model Architecture
* Training
* Evaluation
* Results
* License
* Installation
  
## To run this project, you need to have Python installed along with the following libraries:
* TensorFlow
* Keras
* NumPy
* Matplotlib

## You can install the required libraries using pip:
### pip install tensorflow keras numpy matplotlib

## Dataset
The dataset used for this project consists of images of dogs from 120 different breeds. Each image is labeled with its respective breed.

## Model Architecture
The model is a Convolutional Neural Network (CNN) designed to classify images into 120 different classes (dog breeds). The architecture consists of the following layers:

* Conv2D
* MaxPooling2D
* Flatten
* Dense
* Dropout
* Training
The model is trained using the Adam optimizer and categorical cross-entropy loss. The training process includes data augmentation to improve generalization.

## Evaluation
The model is evaluated using accuracy metrics on the validation dataset. Additional metrics such as precision, recall, and F1-score are also calculated.

## Results
The model achieves an accuracy of approximately 76% on the validation dataset. The confusion matrix and classification report provide insights into the performance for each breed.
