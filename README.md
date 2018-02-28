# Perceptron-Iris-Classification

## Overview:
This is a simple perceptron model which is trained to classify samples from the iris dataset. This model consists of two input features of both the petal and sepal length for each of the Seratos and Vericolor iris species. <br/>

## Requirements:

Python3: https://www.python.org/ <br/>

NumPy: http://www.numpy.org/ <br/>

Pandas: https://pandas.pydata.org/ <br/>

Matplotlib: https://matplotlib.org/ <br/>

## Model:

<p align="center">
  <img src="https://github.com/Gregory-Eales/Perceptron-Iris-classification/blob/master/Images/Perceptron%20Diagram.png" width="500"/>
</p>

This is a diagram of the perceptron machine learning model for classification tasks. It shows the process of inputing the features x <sub>m</sub>, where m is the number of features per data sample, and multiplying them by their corresponding weights. The amalgamation of the two components is then summed and inputed into a stepwise activation function, thus producing a classification. The classification is then outputed and the errors fed back into model to check for the purpose, all the while updating the weights accordingly.

## Data:

<p align="center">
  <img src="https://github.com/Gregory-Eales/Perceptron-Iris-classification/blob/master/Images/Example%20Data%20Table.png" width="400"/>
</p>

The features used in this training example are the petal and sepal length of the seratosa and verisolor iris species. This is the format of the chart with the given data. Each flower has 50 data samples and thus 50 data points for the perceptron to train and classify from.


<p align="center">
  <img src="https://github.com/Gregory-Eales/Perceptron-Iris-classification/blob/master/Images/Iris%20Data.png" width="500"/>
</p>

This is a graph showing plots of petal length vs sepal length. The setosa species is show as red dots and the versicolor species is shown as blue 'X's. There is a clear gap between the two species on the graph which should be easy for a perceptron model to identify.

## Training:

<p align="center">
  <img src="https://github.com/Gregory-Eales/Perceptron-Iris-classification/blob/master/Images/Misclassification%20Errors.png" width="500"/>
</p>

This graph shows the number of misclassifications the perceptron model makes for each epoch. The number of misclassifications begins to drop after the third epoch with an error rate of 0% only after five epochs.

## Results:

<p align="center">
  <img src="https://github.com/Gregory-Eales/Perceptron-Iris-classification/blob/master/Images/Classified%20Iris%20Data.png" width="500"/>
</p>

This graph shows the decision regions for each species in their corresponding color labeling. The linear distinction makes a clear separation between the species, showing that the perceptron has successfully learned how to predict the species type given the sepal and petal length.

# Sources:

* Raschka, Sebastian, and Randal S. Olson. Python Machine Learning: Unlock Deeper Insights into Machine Learning with This Vital Guide to Cutting-Edge Predictive Analytics. Birmingham: Packt Publishing, 2016. Print.

* R.A. Fisher. “Iris Data Set.” UCI Machine Learning Repository: Iris Data Set, 1936, archive.ics.uci.edu/ml/datasets/iris.


