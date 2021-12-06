# Distracted-Driver-Detection--DeepLearning
# Deep learning classification model to detect drivers state :
---
Every day about 13 people in the Saudi Arabia are killed in crashes.People who use their cell phones to talk or text while driving are by far the most common reason for distracted driving accidents. 

>In this project our task was to get a dataset to build an deep learning classification model on. We chose to analyze a dataset obtained from kaggle that collects an images for the drivers state .
>Goals:
Build Deep learning classification model to predict the state of the driver .

## Data Collection :
---
>**We chose the State Farm Distracted Driver Detection dataset for this project:**
>- The dataset was obtained from  this website https://www.kaggle.com/c/state-farm-distracted-driver-detection/data 
>- the dataset contains 10 classes each class contains around 2000 images .

 
## Prepossessing:
---
#### Dataset Before:
Training dataset: 10 classes 22,024 images

Test dataset: 2400 unlabelled images

#### Dataset After:
Training dataset: 3 classes 19624 images

Validation dataset: 3 classes 2400 images

Test dataset: 3 classes 2400 images

- Image size:150*150
- Reshape  
## EDA graph:
---

>This graph shows the number of images for each class in the training set.
<img src="EDA Graph_2.png">


## Modeling:
----

###   Baseline models:

<img src="Baselin_ models.png">
###  CNN models:

<img src="CNN_models.png">

###  Best Models:

<img src="Best_Models.png">

### Best Model (VGG16) :
<img src="Best Model (VGG16).png">

#### Results:
Train Accuracy: 0.998618 

Train Precision: 0.995899 

Recall: 0.998999 

F1 score: 0.997436 

Test Accuracy: 0.930417 

Test Precision: 0.933343 

Test Recall: 0.929644 

Test F1 score: 0.930894 

### Confusion Matrix


## Conclusion:
---
Most models give us a good results in the both training and validation set and no overfitting .
VGG16 shows best result in the test set . 

## Future work:
---
- Collect more images from different angle.
- Tuning the models (different number of units and layers change the values of the hyperparameter )
