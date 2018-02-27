# Perceptron-Iris-Classification

## Overview:
This is a simple perceptron model which is trained to classify samples from the iris dataset. This consists of two input features of both the petal and sepal length for each of the Seratos and Vericolor iris species. <br/>

## Requirements:

Python3: https://www.python.org/ <br/>

NumPy: http://www.numpy.org/ <br/>

Pandas: https://pandas.pydata.org/ <br/>

Matplotlib: https://matplotlib.org/ <br/>

## Model:

<p align="center">
  <img src="https://github.com/Gregory-Eales/Perceptron-Iris-classification/blob/master/Images/Perceptron%20Diagram.png" width="500"/>
</p>

This is a diagram of the perceptron machine learning model for classifacation tasks. This shows the proccess of inputing the features x <sub>m</sub> where m is the number of features per data sample, and mulitplying them by their corresponding weights. The amalgamation of the two components is then summed and inputed into a stepwise Activation function producing a classification. The classification is then outputed and the errors fed back into model to check for the purpose updating the weights accordingly.

## Data:

<p align="center">
  <img src="https://github.com/Gregory-Eales/Perceptron-Iris-classification/blob/master/Images/Example%20Data%20Table.png" width="400"/>
</p>

The features used in this training example are the petal and sepal length of the seratosa and verisolor iris species. This is an chart example with the given data. Each flower has 50 data samples and thus 50 data points for the perceptron to train and classify from.


<p align="center">
  <img src="https://github.com/Gregory-Eales/Perceptron-Iris-classification/blob/master/Images/Iris%20Data.png" width="500"/>
</p>

This is a graph showing plots of petal length vs sepal length. The setosa species is show as red dots and the versicolor species is shown as blue x's. There is a clear gap between the two species on the graph and should be easy for a perceptron model to identify.

## Training:

<p align="center">
  <img src="https://github.com/Gregory-Eales/Perceptron-Iris-classification/blob/master/Images/Misclassification%20Errors.png" width="500"/>
</p>

This graph shows the number of misclassifications the perceptron model makes for each epoch. The number of misclassifications drops off sharply after the 3rd epoch with an error rate of 0% there after.

## Results:

<p align="center">
  <img src="https://github.com/Gregory-Eales/Perceptron-Iris-classification/blob/master/Images/Classified%20Iris%20Data.png" width="500"/>
</p>

This graph shows the decision regions for each species in there corresponding color labeling. The linear distiction makes a clear seperation beween the species and has succesfully learned how to predict the species type given the sepal and petal length.

# Sources:

* Raschka, Sebastian, and Randal S. Olson. Python Machine Learning: Unlock Deeper Insights into Machine Learning with This Vital Guide to Cutting-Edge Predictive Analytics. Birmingham: Packt Publishing, 2016. Print.

* R.A. Fisher. “Iris Data Set.” UCI Machine Learning Repository: Iris Data Set, 1936, archive.ics.uci.edu/ml/datasets/iris.


