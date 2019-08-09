# Sparkify Project
This project is the final Capstone project of the Udacity Data Scientist Nanodegree program. The aim is to learn how to manipulate realistic datasets with Spark to engineer relevant features for predicting churn. Input data is related to the fictive music streaming service Sparkify (similar to Spotify and Pandora).

# Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Project Process](#process)
5. [Result Summary](#result)
6. [Licensing, Authors, Acknowledgements](#licensing)

# Installation <a name="installation"></a>
The code should run with no issues using Python versions 3. See the requirements.txt file for details about library versions.

# Project Motivation <a name="motivation"></a>
Since I'm a long time user of the Spotify streaming service I've wanted to test out some ideas for a while. In this project I could work with similar data and also try out Spark which is new to me.

# File Descriptions <a name="files"></a>
- **mini_sparkify_event_data.json**: Fictious music streaming data provided by Udacity.
- **sparkify.ipynb**: Exploratory notebook with all steps necessary to build a model that predicts churn for the Sparkify data.

# Project Process <a name="process"></a>
When working with this project I followed the CRISP-DM process. The details are found in the notebook and also on this blog post:
<link>

# Result Summary <a name="result"></a>
The model result was not that good. As the dataset available was very small, it's hard to trust the model in it's current state. It should be trained and validated further on a greater dataset. Please see the blog mentioned above to read the complete results.

# Licensing, Authors, Acknowledgements <a name="licensing"></a>
## Code
See details in licensing file.

## Data
Data in the .json file cannot be used without consent from Udacity.

## Acknowledgements
Besides the Udacity training material, the following resources were of much help in this project:
- https://mapr.com/blog/predicting-breast-cancer-using-apache-spark-machine-learning-logistic-regression/
- https://stackoverflow.com/questions/36132322/join-two-data-frames-select-all-columns-from-one-and-some-columns-from-the-othe
- https://stackoverflow.com/questions/38664620/any-way-to-access-methods-from-individual-stages-in-pyspark-pipelinemodel?rq=1
