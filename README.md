# AI-Hardware-and-Tools

<!-- OL -->

1. Project 1

## Gender detection ( Tiny ML)

We have used a simple convolutional neural network architecture, similar to the CaffeNet and AlexNet. The network uses 3 convolutional layers, 2 fully connected layers and a final output layer. The details of the layers are given below.

<!-- UL -->

- Conv1 : The first convolutional layer has 96 nodes of kernel size 7.

- Conv2 : The second conv layer has 256 nodes with kernel size 5.

- Conv3 : The third conv layer has 384 nodes with kernel size 3.

The two fully connected layers have 512 nodes each.
We have framed Gender Prediction as a classification problem. The output layer in the gender prediction network is of type softmax with 2 nodes indicating the two classes “Male” and “Female”.
Predict Gender
We will load the gender network into memory and pass the detected face through the network. The forward pass gives the probabilities or confidence of the two classes. We take the max of the two outputs and use it as the final gender prediction.
Display Output
We will display the output of the network on the input images and show them using the imshow function.

1. Project 2

## Heart disease analysis ( Data analysis using R)

Healthcare industries generate enormous amount of data, so called big data that accommodates hidden knowledge or pattern for decision making. The huge volume of data is used to make decision which is more accurate than intuition. Exploratory Data Analysis (EDA) detects mistakes, finds appropriate data, checks assumptions and determines the correlation among the explanatory variables.
We have taken the dataset from kaggle
The dataset holds around 300 records with 8 attributes such as age, chest pain type, blood pressure, blood glucose level, ECG in rest, heart rate and four types of chest pain.
We have analysed and understand the relationship between various attributes leading to heart attacks.
We have performed the data analysis using R programming language, an open-source language used for statistical computing or graphics. This programming language is often used in statistical analysis and data mining. It can be used for analytics to identify patterns and build practical models. R not only can help analyze organizations’ data, but also be used to help in the creation and development of software applications that perform statistical analysis

1. Project 3

## E commerce stats ( using PowerBI)

Power BI is an interactive data visualization software product developed by Microsoft with primary focus on business intelligence. It is part of the Microsoft Power Platform. Power BI is a collection of software services, apps, and connectors that work together to turn unrelated sources of data into coherent, visually immersive, and interactive insights. Data may be input by reading directly from a database, webpage, or structured files such as spreadsheets, CSV, XML, and JSON.

In this project we have visualized the growth of a company in 4 years golably it tells from different graphs how and which area the sale has improve and where was less sales this year.

1. Project 4

## Diabetes Prediction ( using Pyspark)

Apache Spark is an open-source, distributed processing system used for big data workloads. It utilizes in-memory caching, and optimized query execution for fast analytic queries against data of any size. It provides development APIs in Java, Scala, Python and R, and supports code reuse across multiple workloads—batch processing, interactive queries, real-time analytics, machine learning, and graph processing.

We have made a model which predicts whether a patient has diabetes or not. We have used Pyspark for this

PySpark is an interface for Apache Spark in Python. It not only allows you to write Spark applications using Python APIs, but also provides the PySpark shell for interactively analyzing your data in a distributed environment. PySpark supports most of Spark’s features such as Spark SQL, DataFrame, Streaming, MLlib (Machine Learning) and Spark Core.

1. Project 5

## React static site containerised using Docker ( Devops)

In this Project, We have made a static React app using ReactJS, NextJS, TailwindCSS, HTML, CSS which we have later containerised using Docker.
Containerization has become a major trend in software development as an alternative or companion to virtualization. It involves encapsulating or packaging up software code and all its dependencies so that it can run uniformly and consistently on any infrastructure. The technology is quickly maturing, resulting in measurable benefits for developers and operations teams as well as overall software infrastructure.

It is a majour part of Devops. We learned a lot about Devops while developing this app.

DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes.
