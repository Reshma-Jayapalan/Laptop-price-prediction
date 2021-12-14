# Introduction
This project is for predicting the price of laptop. This is a regression problem and we handle this project from data cleaning, prediction to deployment.
The original dataset and problem is from Kaggle, [Laptop Price](https://www.kaggle.com/muhammetvarl/laptop-price).
The same is also uploaded in this repository.

# Problem Statement
There are many different brands of laptops available in the market, with varying varieties in the processor to RAM to the type and size of memory. And the price of these laptops also vary accordingly. With the given dataset, we are trying to explore the features that most affect the price and predict the price using these variables.

As per the dataset, below are the variables and their description:
+ Company-Laptop Manufacturer
+ Product-Brand and Model
+ TypeName -Type (Notebook, Ultrabook, Gaming, etc.)
+ Inches-Screen Size
+ ScreenResolution -Screen Resolution
+ Cpu-Central Processing Unit (CPU)
+ Ram -Laptop RAM
+ Memory -Hard Disk / SSD Memory
+ GPU-Graphics Processing Units (GPU)
+ OpSys -Operating System
+ Weight-Laptop Weight
+ Price_euros-Price (Euro)

# Repository Contents
+ `notebook.ipynb` - Jupyter notebook that contains data cleaning, data preparation, EDA, model building etc
+ `train.py` - Training the final model,Saving it to a file using pickle
+ `predict.py` - Loading the model,Serving it via a web serice (e.g. with Flask)
+ `pipenv` and `pipenv.lock` for the virtunal environment using pipenv
+ `Dockerfile` for using a Docker container
+ Deployment

# Deployment
## 
##
##

# References
This project is part of the Midterm project for the [Machine Learning Zoomcamp](https://github.com/alexeygrigorev/mlbookcamp-code/tree/master/course-zoomcamp) conducted by **Alexey Grigorev**
