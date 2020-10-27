### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
Libraries used: 
1. pyspark, 
2. pandas, sklearn, numpy, matplotlib, datetime, operator, collections, os
There should be Spark installed on the machine where this notebook is tested. To run the code also the Anaconda distribution of Python is needed.  
To make sure the code runs with no issues, please use Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was using the 128MB subset of large 12GB dataset, which represents log data of fictional music streaming service called Sparkify. This data was provided by Udacity.
The goal of this project was to explore and clean the data, create a useful set of features and train a model which would be able to predict a customer churn.

## File Descriptions <a name="files"></a>

There is 1 notebook available here to showcase work related to the above goal description. The notebook consists of 4 main parts:  Load and Clean Dataset, Exploratory Data Analysis, Feature Engineering and Modeling.
Markdown cells were used to assist in walking through the thought process for individual steps.  

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here]( https://mt-svitek.medium.com/music-streaming-service-churn-predictions-with-pyspark-b4c788ac0c5b).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit to Udacity for the data and Spark-based Workspace provided!
