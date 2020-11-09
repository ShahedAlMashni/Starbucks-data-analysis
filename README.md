# Starbucks-data-analysis
## Overview
An analysis of a data set that contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Different features in the dataset were analyzed and classification models were built to predict how a user would respond to an offer. 
For a more descriptive analysis, check out this [Medium Article](https://shahedmashni.medium.com/analyzing-starbucks-app-data-9f9c3cce06ca) that I wrote. 

This project is done as part of Udacity Data Science Nanodegree - capstone project.

# Table of contents
1. [Getting Started](#par1)
3. [Project Summary](#summary)
3. [Datasets](#datasets)
4. [License](#License)
5. [Contact](#Contact)

## Getting Started <a name="par1"></a>

This project uses the following libraries:
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [sklearn](https://scikit-learn.org/stable/)
* [python](https://www.python.org/download/releases/3.0/)


In order to get a local copy of the project, you will need to download the dataset from the data folder, and add it to the same folder of the project.   
The project has the following:
- Starbucks_Capstone_notebook.ipynb
- data folder

The jupyter notebook contains all code and data analysis.

Download the [jupyter](https://jupyter.org/) notebook from this repository and have fun!

## Project Summary <a name="summary"></a>
In this project, I will be analyzing data coming out of this app and try to find trends and relations between users information and offer data. Finally, I will build a machine learning model to predict whether a user will respond to an offer or not. 

Each user on the application has an account that can include demographic information on the user. A user can make a purchase, receive an offer, view an offer or complete an offer.
There are three types of offers that can be sent: buy-one-get-one (BOGO), discount, and informational.
* BOGO: a user needs to spend a certain amount to get a reward equal to that threshold amount.
* Discount: a user gains a reward equal to a fraction of the amount spent.
* Informational: mere advertisement for a drink 

**Problem Statement:**   
The problem that we are trying to answer is how does a customer respond when an offer is sent to them.
The strategy that we will be following is:
1. Data preprocessing and cleaning: we will look deeper at the data and understand its content. Data will then be cleaned from anomalies, null values, and duplicates.
2. Data analysis and visualization: data will be further analyzed and visualized to answer more detailed questions relating to our problem.
3. Data modelling: we will try to build a machine learning model that will predict whether a user will complete an offer or not. model is evaluated based on f1-score.

## Dataset <a name="datasets"></a>

Datasets:
There are three datasets available:
* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

Further information on the dataset can be found in the Jupytr notebook.

## License <a name="License"></a>
Distributed under the MIT License. See `LICENSE` for more information.

## Contact <a name="Contact"></a>
Shahed - shahedmashni@gmail.com
