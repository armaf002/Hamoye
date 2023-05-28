# Assignment INTRODUCTION TO PYTHON FOR MACHINE LEARNING GRADED QUIZ

This repository contains the code for the assignment on Introduction to Python for Machine Learning. The assignment is based on a dataset provided by the Food and Agriculture Organization of the United Nations.

## Dataset

The dataset is available in CSV format and can be accessed from the following GitHub link: [Food and Agriculture Organization Dataset](https://github.com/HamoyeHQ/HDSC-Introduction-to-Python-for-machine-learning)

The dataset contains the following features:

- Area Code
- Area
- Item Code
- Item
- Element Code
- Element
- Unit
- Y2014
- Y2015
- Y2016
- Y2017
- Y2018

## Loading the Dataset

To correctly read the dataset for the quiz, I ensured to specify the encoding value as "latin-1". Here's an example of how I loaded the dataset with the appropriate encoding in my code:

```python
import pandas as pd

# Load the dataset
dataset = pd.read_csv('dataset.csv', encoding='latin-1')
