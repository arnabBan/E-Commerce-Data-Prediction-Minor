# E-Commerce-Data-Prediction-Minor 

## Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Run](#run)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [Credits](#credits)



## Overview
This is a simple E-Commerce Data prediction project using Python. This dataset is used to predict whether a product is likely to get shipped on time or not based on the input parameters like gender, mode of shipment, discount offered, cost of the product, and product importance etc. Each row in the data provides relavant information about the patient. An international e-commerce company based wants to discover key insights from their customer database. They want to use some of the most advanced machine learning techniques to study their customers. The company sells electronic products. 

## Motivation
What could be a perfect way to utilize unfortunate lockdown period? Like most of you, I spent my time in cooking, Netflix, youtube, coding and reading story book. I was facing problem to get a job in that situation. That time I have joined in data analytics course for learning more and getting relief from this situation. In this training I had to do a minor project. That's why I have chosen this project to know more about e-commerce data and predicted on this data.

## Technical Aspect
This project is divided into three part:
1. I have taken datasets from internet and did some exploratory data analysis, statistical analysis using pandas and used matplotlib, seaborn for more infomative and attractive visualization of data.
2. Applied different types of encoders for converting categorical feature to numerical feature. After that applied standardscaler for grouping the data which helps to get best output through machine learning models.
3. Applying two machine learning models 1)Logistic Regression, 2)Random Forest Classifier.
    - I got higher accuracy, precision value, recall value, f1-score value in Random Forest Classifier then Logistic Regression. Random Forest Classifier is usually           robust to outliers and can handle them automatically Random forest can solve both type of problems that is classification and regression. That's why I have chosen       Random Forest Classifier for prediction.
    - Used confusion matrix for checking there is any error is present or not and the data is giving biased output or not.
    - Used classification report for finding precision, recall and f1-score values because we can not fully trust on accuracy score.

## Installation
The Code is written in Python 3.9.2 version. If you don't have Python installed you can find it [here](https://www.python.org/downloads/) and ananconda then you can find it [here](https://www.anaconda.com/products/individual). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip or conda. You can install in libraries in two way 1)in anaconda prompt 2)in jupyter notebook:
```bash
pip install package_name (anaconda prompt)

!pip install package_name (jupyter notebook)
```

## Run
> STEP 1
#### Linux, macOS, Windows User
I don't have too much knowledge in linux or macOS that's why I can not say more about it.
Firstly, you have to download editor then download required libraries. After that download data set and the ipynb file from here.

> STEP 2

To run the project in a local machine, just keep either data set and ipynb file in same directory or I have mentioned the data set path in the notebook, like that you can do also. After that execute all the code line by line then you will get it.

## To Do
1. Move to run another online editor if local machine is not enough capable to execute it, i.e. google colab.
2. For getting more better and proper vizualization chart then you can open editor in chrome browser.

## Bug / Feature Request
If you find a bug (the notebook couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/arnabBan/E-Commerce-Data-Prediction-Minor/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/arnabBan/E-Commerce-Data-Prediction-Minor/issues/new). Please include sample queries and their corresponding results.

## Technologies Used

[<img target="_blank" src="https://forthebadge.com/images/badges/made-with-python.svg" width=200>](https://www.python.org/downloads/)

[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/320px-NumPy_logo_2020.svg.png" width=200>](https://numpy.org/) [<img target="_blank" src="https://github.com/pandas-dev/pandas/blob/master/web/pandas/static/img/pandas.svg" width=170>](https://pandas.pydata.org/)[<img target="_blank" src="https://matplotlib.org/_static/logo2_compressed.svg" width=280>](https://matplotlib.org/) [<img target="_blank" src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width=200>](https://seaborn.pydata.org/)[<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=270>](https://scikit-learn.org/stable/)[<img target="_blank" src="https://jupyter.org/assets/main-logo.svg" width=270 height=150>](https://jupyter.org/)

## Team
[<img target="_blank" src="https://avatars.githubusercontent.com/u/45432311?s=400&u=13a1e5f20beaf9fa166fbb89eac71cd8617c92eb&v=4" width=150 height=150>](https://www.linkedin.com/in/arnab-banerjee-94218a9a/) |
-|
[Arnab Banerjee](https://www.linkedin.com/in/arnab-banerjee-94218a9a/) |)

## Credits
- [Kaggle](https://www.kaggle.com/prachi13/customer-analytics) - This project wouldn't have been possible without this. It saved my enormous amount of time while collecting the data. A huge shout-out to its creator [Prachi Gopalani](https://www.linkedin.com/in/prachi-gopalani-954640ba/).
