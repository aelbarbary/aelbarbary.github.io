---
layout: post
title: Introduction to Machine Learning (ML)
comments: true
---

![_config.yml]({{ site.baseurl }}/images/ml.png)

### Definition

* Machine learning is the algorithmic discovery of patterns in data
* It is used to find meaningful patterns and applying it to a task
* example tasks:
  * recognizing pictures that contains human faces
  * recognizing if a transaction is a fraud or not.
  * recognizing if a picture/movie is appropriate for children or not.
* A pre-requisite to it is to have data ... a lot of data
* Allows the data to speak for itself and allows to automatically update
your system.

### When ML is the right choice ?

* ML excels when the task requires many cases of weak evidences whose
importance is unknown or changing overtime.

### Machine Learning Process ... 4 steps

* Problem Framing: You get to know the context of your problem. you translate you business problem to a machine learning Problem
* Data Handling: You take the huge volume of raw data you have and you prepare for modeling step
* Modeling: Training the machine leaning model is the most technical step in the process
* Application: Put you application in production

### Step 1: Problem Framing

* Understand the business context
  * You need to speak to domain experts (technical and non-technical)
  * You need to ask a lot of questions
* Identify the baseline
  * having a baseline will give you the chance to do "Opportunity Analysis"
  * Having a baseline will help you comparing the old system to the new ML model
* Translate the business problem to a ML problem

### Step 2: Data Handling
* Label: This is the value that the ML model trying to predict
* Features: The bits of information we use to predict the labels
* Data Point: the label + the Features
* Steps of Data Handling
  * Manual analysis: does the data seems enough to make good predictions
  * Visualize your data points: It will help you spot patterns
  * Train/Development/Test: You divide you data into three sets
    * train (80%): You use this set to train the model
    * development (10%): you use this to compare the performance of you model. you might need to change data or model algorithms and re-train
    * test: you run the predictions one last time on test. and this should be the performance that you see in production assuming that the world has not changed a lot by the time you deployed you model

### Step 3: Modeling
* How to evaluate your model performance
    * Accuracy: The number of times the predicted label matched the true label
    * Precision: TP / (TP + FP)
    * Recall: TP / (TP + FN)
* How to enhance your model performance
    * Increasing the data volume can help the model makes better decisions. but this saturates after certain amount of time.
    * Feature Engineering: Is the transformation of your raw data to help the model makes better decisions
