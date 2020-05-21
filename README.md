# COVID-19-Pneumonia-Detection


## Problem Definition
The novel coronavirus (COVID-19) is a pandemic that has infected millions of people around the world. COVID-19 affects the respiratory system of the human body, and one of its complications is the pneumonia that is caused due to it, which can be life threatening. This pneumonia is detected using the X-rays of the patients. However, the difference between COVID-19 pneumonia and viral pneumonia is very difficult, even for medical experts to scan visually.

To help eliminate this problem, a Deep Learning model that distinguishes the x-ray images as COVID-19 pneumonia, viral pneumonia and a healthy patient was built. To implement this, Convolution Neural Networks (CNN) have been used on the patient's chest X-Ray images.
Apart from this, the Support Vector Machine classifier and Multi-Layer Perceptron are also implemented as baseline classifiers. The aim of this project is to maximize the accuracy using different methods mentioned above, because wrong diagnosis in the medical community could cause a huge impact, and could even be fatal.

COVID-19 radiography dataset from kaggle: https://www.kaggle.com/tawsifurrahman/covid19-radiography-database

Methodology:

- Pre-processing:
  - Data Augmentation
  - Resizing the images
  - Adding class labels
  - Train-validation-test split
  
- Classification
 
 Baseline Models:
  - SVM
  - NN
  
  Convolutional Neural Networks:
  - ResNet-50
  -VGG-19
  
## Conclusion
After trying the 4 different algorithms to detect and distinguish pneumonia caused due to COVID-19, the VGG-19 model outperformed the other models and yielded an accuracy of 100%
