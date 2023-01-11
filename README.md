# Dogs vs. Cats Classification
Using Machine Learning and Deep Learning to detect the class of target (Dog or Cat) using significant features given by the most linked features that are taken into consideration when evaluating the target.

## Table of Contents
* [Introduction](#introduction)
* [Dataset General info](#dataset-general-info)
* [Evaluation](#evaluation)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Run Example](#run-example)
* [Sources](#sources)

## Introduction
Because of the rapid of scientific and technical development in all fields, the progress in the fields of Artificial Intelligence has become a necessity to keep pace with it, also support the process of development in all these fields, especially scientific ones, and one of these important fields is Computer Vision, with the aim of refining and showing my theoretical and practical skills acquired from my past studies in the field of Computer Vision, refining it gradually within practical projects to show as much detail as possible related to Computer Vision and thus give benefit to those who are new to this field when reviewing the code,
Based on this introduction, I present to you my project in solving the problem of Cats vs Dogs, and my suggestions for solving it with the best possible ways and the current capabilities using Machine Learning, and Deep Learning.\
This is the beginning of a group of Computer Vision projects, the level of projects will be progressed gradually in the upcoming projects based on my experience.

## Dataset General info
**General info about the dataset:**

    This Dataset is an online based dataset, and we can fetch it using: !wget https://download.microsoft.com/download/3/E/1/3E1C3F21-ECDB-4869-8368-6DEBA77B919F/kagglecatsanddogs_5340.zip
    
## Evaluation
The accuracy score is using to evaluate the performance, because of the balanced dataset.
## Technologies
* Programming language: Python.
* Libraries: Numpy, Matplotlib, Pandas, Seaborn, sklearn, tensorflow, warnings, os, PIL. 
* Application: Jupyter Notebook.

## Setup
To run this project setup the following libraries on your local machine using pip on the terminal after installing Python:\
'''\
pip install numpy\
pip install matplotlib\
pip install pandas\
pip install seaborn\
pip install scikit-learn\
pip install tensorflow\
pip install os-sys\
pip install pytest-warnings\
pip install Pillow\
'''\
To install these packages with conda run:\
'''\
conda install -c anaconda numpy\
conda install -c conda-forge matplotlib\
conda install -c anaconda pandas\
conda install -c anaconda seaborn\
conda install -c anaconda scikit-learn\
conda install -c conda-forge tensorflow\
conda install -c jmcmurray os\
conda install -c bioconda perl-warnings-register\
conda install -c anaconda pillow\
'''

## Features
* I present to you my project solving the problem of Dogs vs. Cats Classification using CNN and some effective algorithm and techniques with a good analysis (EDA), and comparing between them using logical thinking, and put my suggestions for solving it in the best possible ways and the current capabilities using Machine Learning, and CNN.

### To Do:
**Briefly about the process of the project work, here are (some) insights that I took care of it:**

* Perform files check is used to ensure that files are valid and of the same format (image format).
* Create DataFrame of Input and Output to better deal with the data.
* Doing EDA to ensure the status, correctness and type of images and to ensure the balance of the data.
* Create DataGenerator for the training images and the idea of data augmentation was used
* Trained with adam optimizer algorithm, and binary_crossentropy loss algorithm.
* Feature extraction from the model.
* Visualize the results, whether training accuracy and error.

## Run Example
To run and show analysis, insights, correlation, and results between any set of features of the dataset, here is a simple example of it:

* Note: you have to use a jupyter notebook to open this code file.

1. Run the importing stage

2. Run the dataset

3. Select which cell you would like to run and show its output.

4. Run Selection/Line in Python Terminal command (Shift+Enter)

## Sources
This data was taken from microsoft/
(https://download.microsoft.com/download/3/E/1/3E1C3F21-ECDB-4869-8368-6DEBA77B919F/kagglecatsanddogs_5340.zip)
