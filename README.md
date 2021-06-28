# This is a Capstone Machin learning Project that has been done as a final project in udacity’s Nanodegree Data Science program using Spark technology. we’ll focus on Sparkify, its full dataset is 12GB, of which a subset was provided by Udacity in the workspace (Github repository). Also, there is an option to choose Spark cluster on the cloud using AWS or IBM Cloud to analyze the full dataset.
Predicting customers’ behavior is important for businesses, and it is a very challenging task. Data science can assist in peredicticting users’ needs . Predicting user churn rate is one of the most challenging and common tasks that are necessary for any customer-oriented business. In this project, we created a model to predict churn.
In this project, we have estimated whether users of a fictitious audio streaming platform are likely to unsubscribe, based on their activity logs.

## Table of Contents

1. [Installation](#installation)
	* [Dependencies](#dependencies)
2. [Project Motivation](#motivation)
3. [File Description](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

### Installation: <a name="installation"></a>
#### Dependencies <a name="dependencies"></a>
In addition to the Anaconda distribution of Python versions 3.5+, please install the following packages: 
* NumPy, Matplotlib, Seaborn  
* PySpark

### Project Description & Motivation: <a name="motivation"></a>
This spark machine learning capstone project was implemented in predicting customer churn. First, all the necessary preprocessing and data wrangling have been done including null and duplicate value checking as well as converting time stamp and registration time to obtain cleaner data as much as possible. Mostly based on our exploration part, We determined 10 features and also the churn label to creating our model. We trained four different kinds of classification models on our data (including Logistic Regression, Support Vector Machines, RandomForest, and Gradient Boosted Trees. After comparing the performance of all 4 models and RandomForestClassifier and Logistic regression performed better so they are selected as our final models to do some grid search to improve the performance of the model. After Tuning Hyperparameters and doing a grid search that last about 2 hours, I haven’t seen any changes in performance.
#### Improvement Recommendations
I think we can do much work on feature engineering and test some more features and their impacts on creating a reliable and accurate model. We can also create a much more accurate and reliable model with much more data for training. We also need to be sure that the data we are working on is accurate because inaccurate data can result in wrong predictions.
#### Reflection
With this project, I got familiar with building data science projects on Apache Spark which is necessary for big data applications. Customer churn is one of the greatest threats for all companies and they need to be doing all necessary works to maintain their customers. It was a great experience for me to work with different modules under PySpark and understanding its functionality, data frame, and overall architecture. The biggest challenge in this project was to identify features that impact how likely a customer will churn or not. Determining the right features will determine the performance and accuracy of the model.

### File Description: <a name="files"></a>
There is a notebook available here to showcase work related to this project. The notebook is exploratory in searching through and working with the data pertaining to the churn rate prediction of the subject in hand, and markdown cells were used to assist in walking through the thought process for individual steps.  

## Results<a name="results"></a>
The main findings and research for this project can be found in the post available [here](https://iranmehrazadeh.medium.com/sparkify-the-big-data-capstone-project-f9c4c819d8be).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Udacity for the data, which won't be accessible unless you are enrolled in this nanodegree program.  Otherwise, feel free to study and refer to this project as you would like! 