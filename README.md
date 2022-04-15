# Segmented Nuclei Images
This dataset contains a large number of segmented nuclei images. In this project, the model will be trained to do segmentation of nuclei.

## Introduction
This is a project assigned during the Deep Learning with Python MUP-AI05 course, one of the course for AI05 bootcamp organized by Selangor Human Resource Development Centre (SHRDC) on 15 April 2022. The data used in this project is obtained from 2018 Data Science Bowl (link: [https://www.kaggle.com/competitions/data-science-bowl-2018/data](https://www.kaggle.com/competitions/data-science-bowl-2018/data)). 

## Methodology
In this project, the neural network model is built with TensorFlow Keras functional API framework. Modules used in this project include:
* numpy
* tensorflow
* matplotlib.pyplot
* datetime
* opencv (cv2)
* clear_output from IPython.display
* pix2pix from tensorflow_examples.models.pix2pix (credit to : https://github.com/tensorflow/examples)

### STEP 1: Load and store of data


### STEP 2: Preparation of data before training


### STEP 3: Model Design

#### The Model flow diagram:
![Model!](/reference/model.png "Model")

### STEP 4: Evaluation of the model
The accuracy and loss of the model are as following diagram
![Epoch Accuracy!](/reference/epoch_accuracy.png "Epoch Accuracy")
![Epoch Loss!](/reference/epoch_loss.png "Epoch Loss")

## Result
#### The actual value of test data vs prediction value:
![Result #1!](/reference/result_1.png "Result #1")
![Result #2!](/reference/result_1.png "Result #2")
![Result #3!](/reference/result_1.png "Result #3")
