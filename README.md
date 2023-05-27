# ND025 Capstone project - The Classification of Rocks
## Machine learning classification
**Completed by nhutnh5**

## Project Scope
In order to anticipate the facies (lithology rock type) in the oil and gas field and to create forecasts for additional wells based on the model, I decided to examine the data from the drilled wells and utilize machine learning in this project. Facies is a key indicator of where oil and gas will be found, and problems arise when there is insufficient information from rock samples. One of the better methods for interpreting for Facie lithology rock type involves using extra data and a machine learning technique:

- **Project Overview**: One of the most crucial responsibilities for geoscientists working on development and exploratory projects is the characterization of facies. The physical, chemical, and biological conditions that a unit underwent throughout the sedimentation process are reflected in the sedimentary facies. In this project, I will analyze the data from 4 wells and the well log information to create a model that will predict the facies-lithology rocktype for further wells.

- **Problem Proposition**: Characterizing facies is one of the most important tasks for geoscientists engaged in development and exploratory projects. The sedimentary facies is a reflection of the physical, chemical, and biological circumstances that a unit experienced throughout the sedimentation process. In order to develop a model that will forecast the facies-lithology rocktype for additional wells, I will in this project study the data from 4 wells as well as the well log information.

- **Metrics**: As a classification strategy in this research, we employed performance metrics including recall, accuracy, and F1-Score.

**The key of performance Metrics** In this study, we used recall, accuracy, and F1-Score performance indicators as a categorization technique.

## Environment Require
The needed libraries are as following:
- numPy
- pandas
- matplolib
- Seaborn (equal or greater than 0.9.0)
- sklearn

## Files structure
- This can be used as a reference for the well log data. [Facies_classification](https://github.com/seg/tutorials-2016/tree/master/1610_Facies_classification)

- The raw file: **facies_data.csv**. In order to differentiate myself from other network users, I used data from my institution for my project.
This well log file has over 27000 lines of data in it, including data on density porosity, bulk density, spontaneous potential, gamma rays, and resistivity. Small deep learning models may be trained and experimented with using the data.

- I have 1 notebook with an explanation of all of my data for the project.

## My blog post

The post contains the major conclusions of the code. [The Classification of Rocks
](https://medium.com/@nhuttommy/rock-type-classification-140b433bb6e3).

## Refer links and articles
- [Robust Scaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.RobustScaler.html)
- [A Neural Network Implementation in Sklearn](https://scikit-learn.org/stable/modules/neural_networks_supervised.html#mlp-tips)
- [The comparation between Accuracy and F1_score](https://medium.com/analytics-vidhya/accuracy-vs-f1-score-6258237beca2)