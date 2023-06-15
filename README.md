## CIFAR-10 Object Recognition using ResNet50

This project aims to demonstrate object recognition on the CIFAR-10 dataset using the ResNet50 deep learning model. The CIFAR-10 dataset consists of 60,000 32x32 color images across 10 different classes, with 6,000 images per class. The ResNet50 model is a convolutional neural network architecture that has achieved state-of-the-art performance on various image classification tasks.

# Prerequisites

Before running the code, make sure you have the following dependencies installed:

* Python (version >= 3.6)
  
* TensorFlow (version >= 2.0)
  
* Keras (version >= 2.4)
  
* NumPy
  
* Matplotlib

  # Dataset
The CIFAR-10 dataset is not included in this repository. To download the dataset, please visit this website: [Kaggle]( https://www.kaggle.com/competitions/cifar-10/data)

Once downloaded, extract the dataset and place it in the data directory.

# Results
After training completes, the script will display the training and validation accuracy over each epoch. Additionally, it will save the model's performance metrics, such as accuracy and loss, in a CSV file named resnet50_cifar10_metrics.csv.

The accuracy also increases to 71% from 31% by using ResNet50.



  
 
