---
title: "Brain Tumor Image Classification"
layout: post
tag: 
- Data Preperation 
- python
- Data Analysis
- Deep Learning

headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: " "
category: projects
author: Bhushan Suryawanshi 
externalLink: false
---

<p align="center">
  <img width="460" height="300" src="/assets/images/brain_tumor.jpg">
</p>

## Brain Tumor Image Classification
<p align='justify'>

Images are used in various fields to make the problem easier to understand. Image processing techniques are most widely 
used in medical imaging to identify the affected area through an X-ray, computed tomography scan(CT scan), 
MRI scan(Magnetic resonance images). These images are used to detect, identify, and locate infections, abnormal growths 
from the human body. Heart diseases, Cancer, Brain tumor, Blood clotting, these are some of the abnormalities that can be 
found by medical imaging techniques. We can use different machine learning techniques to classify different types of brain 
tumors by using MRI. The Convolutional Neural Network (CNN) is a class of deep learning neural networks that are highly 
effective with image classifications.  

</p>  

#### DataSets:

<p align='justify'>
The brain tumor dataset contains 2870 training images. The dataset includes the three kinds of tumor images. 
The three tumors have the following distribution of data. -
    
- 822 Meningioma images. The meningioma type of tumors seen near the top-outer part of the brain. Meningioma is slowly 
growing noncancerous tumors that cause seizures and visual problems. This type of tumors accounting for 37.6% of all 
tumors, and 53.3% of all non-malignant tumors.
</p>

<img width="200" height="300" src="/assets/images/maningioma.png">


- 826 Glioma images. Glioma is an abnormal growth in glial cells present around the neurons in the brain. Gliomas make 
up 81% of malignant brain tumors in adults.


<img width="200" height="300" src="/assets/images/glioma.png">


- 827 pituitary tumor images. Pituitary tumors grow in pituitary glands that affect body functions. Some pituitary 
tumors result in too many of the hormones that regulate important functions of your body. Some pituitary tumors can 
cause your pituitary gland to produce lower levels of hormones. 


<img width="200" height="300" src="/assets/images/pitutary.png">


- 395 No tumor images. 


<img width="200" height="300" src="/assets/images/no%20tumor.png">


Dataset Can be found [here](https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri)


#### Prerequisites/Installations:
- Python 3
- Pandas
- Keras
- TensorFlow
- CNN


#### Analysis

I am using grayscale images hence, the size of each image is smaller compared to using RGB. Following are some sample images of the brain tumor. 

To start with,  I used binary classification to predict tumors. The data used for this model is from the no_tumor and meningioma_tumor class. The data is first converted to grayscale and then resized to 64 x 64 pixel size. The model uses 4 Conv2D and 4 max_pooling layers followed by flattening and dropout layers. The accuracy of the binary model was above 80%. This model is further tuned with hyper-parameters like batch size and epochs.  
The best model shows a validation accuracy of more than 82%.  The use of binary classification here is to verify the data is good for model building. Following are some of the results from the test data. 


As seen in the dataset we have 4 different classes. Hence using multiclass classification model to find the accuracy with different types of tumors. For the multiclass classification, the image resolution of 128 x 128 pixels is used. To make the most of our few training examples, we will "augment" them via a number of random transformations, so that our model would never see twice the exact same picture. This helps prevent overfitting and it generalizes the model better. Keras helps with ImageDataGenerator which can be used for – 
1. Random transformation and normalization.
2. Instantiate generators of augmented image batches
  
``` 
ImageDataGenerator(
        featurewise_center=False,  
        samplewise_center=False, 
        featurewise_std_normalization=False,  
        samplewise_std_normalization=False,  
        zca_whitening=False,  
        rotation_range=0,
        zoom_range = 0,
        width_shift_range=0,  
        height_shift_range=0,  
        horizontal_flip=True,  
        vertical_flip=False)
```

In our case, we will use a very small CNN with few layers and few filters per layer, alongside augmentation and dropout. Dropout helps reduce overfitting, by preventing a layer from seeing twice the same pattern, thus acting in a way analogous to data augmentation. This approach gave us a validation accuracy of around 73%. The model uses 20 epochs with a batch size of 20. 

GitHub repository can be found here: [GitHub]( https://github.com)  
