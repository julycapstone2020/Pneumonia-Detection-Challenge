
# Pneumonia Detection 

This notebook build an end-to-end build a pneumonia detection system, to locate the position of inflammation in an image.

Tissues with sparse material, such as lungs which are full of air, do not absorb the X-rays and appear black in the image. Dense tissues such as bones absorb X-rays and appear white in the image.

While we are theoretically detecting `lung opacities`, there are lung opacities that are not pneumonia related.

## 1. Problem

To locate the position of inflammation in an image.

## 2. Data

In the data, some of these are labeled `Not Normal No Lung Opacity`.This extra third class indicates that while pneumonia was determined not to be present, there was nonetheless some type of abnormality on the image and oftentimes this finding may mimic the appearance of true pneumonia.

Dicom original images: -Medical images are stored in a special format called DICOM files `(*.dcm)`. They contain a combination of header metadata as well as underlying raw image arrays for pixel data.Details about the data and dataset files are given in below link,

https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data

### Pre-Processing, Data Visualization, EDA 

* Exploring the given Data files, classes and images of different classes.
* Dealing with missing values
* Visualizationof different classes 
* Analysis from the visualizationof different classes


### Model Building 

* Building a pneumonia detection model starting from basic CNN and then improving upon it.
* Train the model
* To deal with large training time, save the weights so that you can use them when training the model for the second time without starting from scratch


### Test the Model, Fine-tuning and Repeat

* Test the model and report as per evaluation metrics
* Try different models
* Set different hyper parameters, by trying different optimizers, loss functions, epochs, learning rate, batch size, checkpointing, early stopping etc. for these models to fine-tune them
* Report evaluation metrics for these modelsalong with your observation on how changing different hyper parameters leads to change in the final evaluation metric.

## 3. Evaluation



## 4. Features

