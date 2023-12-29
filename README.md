# Knee Osteoarthritis Disease Prediction

## Overview
This repository contains the code and resources for predicting knee osteoarthritis disease using machine learning techniques. The goal is to develop a model that can accurately predict the presence of osteoarthritis based on relevant features.

## Features
* Data Preprocessing: Comprehensive data cleaning and preprocessing steps to prepare the dataset for modeling.
* Feature Engineering: Identification and extraction of relevant features from the dataset.
* Training Models used: Implementation of a Convolutional neural network using deep learning techniques and then deploying the model using Web-based Flask application.
* Evaluation: Evaluation metrics and results to assess the performance of the models.
* Deployment: Instructions and code for deploying the trained model.

## Dataset
The dataset consists of 1650 digital X-ray images of knee joint which are collected from well reputed hospitals and diagnostic centres. The X-ray images are acquired using PROTEC PRS 500E X-ray machine. Original images are 8-bit grayscale image. Each radiographic knee X-ray image is manually annotated /labelled as per Kellgren and Lawrence grades by 2 medical experts. A novel approach has been developed to automatically extract the Cartilage region (region of interest) based on density of pixels. The target is to evaluate the performance of the deep learning algorithm to predict per Kellgren and Lawrence grades.

## Deployment
* Train the model (here "./Model_Training.ipynb")
* The generated model is saved as model.h5
* Run app.py in visual studio code to get the localhost server - http://127.0.0.1:5000/

# Images: <br>
<div align="center">
  <img alt="ss1" src="./assets/ss1.png" /> <br><br>
   <img alt="ss1" src="./assets/ss2.png" /><br><br>
  
</div>

## Connect with me on Linkedln
https://www.linkedin.com/in/subham-gourisaria-a13418201/
