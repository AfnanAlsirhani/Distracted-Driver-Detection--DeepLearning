
##   Drivers State Detection :
 In this project our task was to get a dataset to build an deep learning classification model. We chose to analyze a dataset obtained from a kaggle that collects an images for the drivers state.


> - We divided the data into three clases(Holding phone,safe driver,distracted driver). 
> - Train datatset: contains  19624 images belonging to 3 classes.
> - Validation dataset: contains 2800 images belonging to 3 classes.
> - Test dataset: contains 2800 images belonging to 3 classes.
> - Three classes :distracted : 0, holding_phone: 1, safe: 2
> -  Then, we rescale the images size to 150 x 150.
> -  Then, we build  DL baseline model.

## Data Collection :

>**We chose the State Farm Distracted Driver Detection dataset for this project:**
>- The dataset was obtained from  this website https://www.kaggle.com/c/state-farm-distracted-driver-detection/data 
>- the dataset contains 10 classes each class contains around 2000 images .



## EDA graph:

**This graph shows the number of images for each class in the training set.**
<img src="EDA Graph_2.png">

##  DL baseline model
**The baseline model is Neural networks model that contains 1 hidden layer of 32 units and the accuracy on train set is 1 and validation set is 0.9986, but still has gaps we need to improve our accuracy and loss.**

<img src="acc_loos graph_2.png">



## Future work:


#### to improve accuracy scores we will  :
- > use CNN and do hyperparameters tuning 
- > use Transfer Learning (VGG16).
- > test our best Model.


