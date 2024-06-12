# Classifying Brain Tumor Images using CNN & Transfer Learning
**Hugo Hiraoka**

In this notebook, we will build an image classifier that can distinguish Pituitary Tumor from "No Tumor" MRI Scan images.

![Brain Tumor](assets/images/brain-tumor1.jpg)


The dataset used in this notebook is available for download from Kaggle.
Although this dataset actually has a total of 3,264 images belonging to 4 classes - Glioma Tumor, Meningioma Tumor, Pituitary Tumor and No Tumor, for this project we have only taken two classes, 
and we are building a binary classification model to classify between the Pituitary Tumor category vs No Tumor.

For this project, we will only use 1000 of these images (830 training images and 170 Testing images). For the training dataset, we will take 395 MRI scans of No Tumor and 435 MRI scans of Pituitary Tumor.
In our problem, we will also be using Data Augmentation to prevent overfitting, and to make our model model more generalised and robust.

We will use this to build an image classification model for this problem statement, and then show how we can improve our performance by simply "importing" a popular pre-trained model 
architecture and leveraging the idea of Transfer Learning.

Model Training accuracy:
![Brain Tumor](assets/images/brain-tumor2.jpg)

Model Testing accuracy:
![Brain Tumor](assets/images/brain-tumor3.jpg)
