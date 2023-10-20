# Data-Science-Projects
I store all the data science projects I do

## Introduction
Human activity recognition (HAR) is the process of identifying and classifying human movements and behaviours based on sensor data. It has various applications in healthcare, sports, and security, among others. In this project, we aim to develop a machine learning model to accurately detect human activity using sensor data.
The aim of the project is to build a system that determines duration of the activity performed by an individual and the type of activity performed by the individual. In order to do this, duration can be found by using the starting timestamp, ending timestamp and heartrate. This is easily possible with the given dataset as all records are provided with an activity ID that corresponds an activity such as: lying, walking, standing, running, etc. This activity ID helps to determine an activity session. Using this information, one can determine the duration of activity session with the help of start and end timestamps of the activity. For real time data, duration can be found with change in heartbeat, as will be shown further. Also, type of activity can be detected by various machine learning models using the columns provided in the dataset.

## Layout
The following layout of the report has been described below:

1.	Data Collection: The first and foremost step is data collection. Data collection is the process of gathering and measuring information on variables of interest, in an established systematic fashion that enables one to answer stated research questions, test hypotheses, and evaluate outcomes. Here, the dataset is provided to us and is called Physical Monitoring dataset and takes up about 1.21 Giga bytes of space.

2.	Data Manipulation: Data manipulation refers to the process of changing or modifying data in some way. This can involve a wide range of activities, including sorting data, summarizing data, merging data from different sources, performing calculations on data, and cleaning and formatting data. In our case, data manipulation starts while collecting data as activity records of each subject is stored in a separate file. Hence, these are merged along the rows to form a dataset. This will be described further in depth.

3.	EDA (Exploratory Data Analysis):  Exploratory data analysis is an approach to analysing and understanding data that is focused on discovering patterns, relationships, and trends in the data, rather than on confirmatory hypothesis testing or model fitting. The goal of EDA is to gain a better understanding of the data and to identify important features, patterns, and trends that may not be immediately apparent. Using the manipulated data, we perform a thorough data analysis and draw conclusions.

4.	Hypothesis Testing: Hypothesis testing is a statistical method used to test whether a hypothesis about a population is true or false. It involves formulating a hypothesis, collecting data, and evaluating the data to determine whether the hypothesis is supported or not.  This section contains two samples drawn from activities that are considered slow and activities that are considered fast. Therefore, using these two samples we reject/ fail to reject the design null hypothesis.

5.	Machine Learning: Machine learning is a method of data analysis that automates analytical model building. It is a subset of artificial intelligence that focuses on the development of computer programs that can access data and use it to learn for themselves. There are many different types of machine learning, including supervised learning, unsupervised learning, semi-supervised learning, and reinforcement learning. Supervised learning involves training a model on labelled data, where the correct output is provided for each example in the training set. Since, the dataset provided is labelled, we are going to follow supervised machine learning techniques.

Following are the sub steps performed in this section:

i)	Dimensionality Reduction

ii)	Modelling

iii)	Results

iv)	Discussion

6.	Conclusion: At last, we conclude about our proceedings with which ones turned out to be appropriate.
