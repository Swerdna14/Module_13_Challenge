# Venture Funding With Neural Networks
**Module 13 Challenge**

In this challenge, we were asked to test out a neural network with given parameters and then asked to alter those parameters to create two different models to see if we could increase the accuracy or decrease the loss of data.

---

## Technologies

The credit risk resampling analysis leverages Python 3.8+ and utilizes the following project libraries and dependencies:
* [Pandas](https://github.com/google/pandas) - Pandas is a powerfull tool for data analysis and manipulation. Pandas provides a plethora of useful functions that make it easy to express, analyze, and manipulate data.

* [scikit-learn](https://scikit-learn.org/stable/) - This is a machine learning library for the python programming language. This library allows for the use of multiple machine learning models, tools, and algorithms.

* [TensorFlow](https://www.tensorflow.org/) - TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries, and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML-powered applications.


---

## Installation Guide

In order to use this program please import and utilize the following libraries and dependencies: 

```python
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
```

---  

### **Run instructions:**
To run this analysis, simply clone the repository or download the files. Open a terminal instance and start a jupyter lab instance by using the following command:
```python
jupyter lab
```
Once it has opened, navigate to the file named **venture_funding_with_deep_learning.ipynb**.

---

## Neural Networks

My first alternative model had an extra hidden layer (3 in total) compared to the original and my second alternative model had an increase number of EPOCHS (increased from 50 to 100). Both decreased the accuracy and increased the loss percentage meaning they were both not as good as the original model.

We then exported all of the models as HDF5 files to save the models.

---

## Contributors

This project was created as part of the module 14 challenge in the Monash University Fintech Bootcamp 2022 Program by:

Lachlan Andrews

Email: swerdna14@gmail.com

LinkedIn: lachlanjandrews
