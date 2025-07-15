[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)
![GitHub language count](https://img.shields.io/github/languages/count/rodrigoalexandre/sph-ecg-arrhythmia-convneuralnetwork)
![GitHub top language](https://img.shields.io/github/languages/top/rodrigoalexandre/sph-ecg-arrhythmia-convneuralnetwork)
![GitHub Repo stars](https://img.shields.io/github/stars/rodrigoalexandre/sph-ecg-arrhythmia-convneuralnetwork)
## **DESCRIPTION**

Project developed for the study presented in the article *"Classification of Cardiac Arrhythmias Based on Electrocardiogram Data Using a Convolutional Neural Network Model"* published by *European Journal of Engineering Science and Technology* (Volume 07, Issue 2, Dec. 2024). 

**Cardiac arrhythmias** are a disease with considerable incidence and prevalence worldwide, and their diagnosis can be complex due to the existence of different types of arrhythmias that share similar characteristics and make an accurate diagnosis difficult. Performing an accurate diagnosis of the type of arrhythmia that affects the individual is essential to assess the severity of the disorder and define the type of treatment most suitable for each case. Several studies have proposed **Machine Learning** and **Deep Learning** models for automatically classifying cardiac arrhythmias to help improve medical processes.

This study proposes a **Convolutional Neural Network** model for classifying cardiac arrhythmias through the analysis of data from electrocardiograms. The proposed model achieved high accuracy in predicting arrhythmias and proved to be a useful tool for dealing with the problem in question..
<br><br>
## **PROJECT STRUCTURE**

|--- source<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- generate-csv-dataset.ipynb (Python code to convert dataset original files to CSV)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- preprocess-sph-dataset.ipynb (Python code to performe the exploratory data analysis)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- conv-neuralnetwork-model.ipynb (Python code to create and train a CNN model)<br>
|--- modelconfig<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- The model configuration files<br>
|--- dataset<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- The dataset location
<br><br>
## **ARTICLE LINK**

https://doi.org/10.33422/ejest.v7i2.1354
<br><br>
## **RESOURCES**
The dataset used in this study is publicly available at: https://doi.org/10.6084/m9.figshare.c.5779802.v1
<br><br>
## **LICENSE**
This project is available under the **MIT license**. See the LICENSE file for more details.
<br><br>
