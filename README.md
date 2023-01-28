# Product Demand Forecast

![# Product Demand Forecast](https://miro.medium.com/max/828/1*xcqe_ST4hDLXPL3YbEHgsg.webp)

<h1>Outline <span class="tocSkip"></span></h1>
<div class="toc"><ul class="toc-item"><li><span><a href="#Datasets" data-toc-modified-id="Datasets-1"><span class="toc-item-num">1&nbsp;&nbsp;</span>Datasets</a></span></li><li><span><a href="#Prerequisites" data-toc-modified-id="Prerequisites-2"><span class="toc-item-num">2&nbsp;&nbsp;</span>Prerequisites</a></span></li><li><span><a href="#Models" data-toc-modified-id="Models-3"><span class="toc-item-num">3&nbsp;&nbsp;</span>Models</a></span></li><li><span><a href="#Results" data-toc-modified-id="Results-4"><span class="toc-item-num">4&nbsp;&nbsp;</span>Results</a></span></li><li><span><a href="#Visualization" data-toc-modified-id="Visualization-5"><span class="toc-item-num">5&nbsp;&nbsp;</span>Visualization</a></span></li></ul></div>

Demand prediction for sales is a critical aspect of any retail business, as it allows companies to forecast future customer needs and plan accordingly. It helps to optimize inventory levels, production schedules, and staffing needs, which can result in significant cost savings and increased profitability. The use of machine learning techniques and models has become increasingly popular in demand prediction, as they can handle large and complex data sets and can be continuously improved over time.

In this project, I will be exploring the use of advanced machine learning and deep-learning techniques for demand prediction of sales. I will be working with real-world data and implementing models that can forecast demand with a high degree of accuracy. By using these models, I aim to provide valuable insights to retailers and help them make better-informed decisions. This project will help businesses to optimize their resources, reduce costs, and increase revenue.

## Datasets

The data consists of real-world examples, separated into three categories: "products", "inventory", and "transactions". These dataframes contain information on sales and inventory for a retail company.

During the [preprocessing step](https://github.com/mahsa-nazari/Product-Demand-Forecast/blob/main/Data%20Cleaning%20and%20Preprocessing.ipynb), I examined the data to find and eliminate features that had high similarity, which helped to improve the model's performance. I also applied methods to prevent data leakage when using merged datasets which .

## Prerequisites

The necessary dependencies could be installed as follows:


```python
pip install -r requirements.txt
```

## Models

The objective of this project is to anticipate the demand for products based on their features. Two approaches have been employed to achieve this goal. Initially, a regression model was utilized with the aim of determining the quantity of sales, which yielded acceptable results despite the limitations of the dataset, which included a portion of randomly generated data. 

To improve the model's performance, it was transformed into a classification problem, with the focus shifting to predicting the level of sales for a product, rather than attempting to pinpoint an exact number. This alteration facilitates the evaluation of the accuracy of predictions and allows for necessary adjustments. 

In the [modelling section](https://github.com/mahsa-nazari/Product-Demand-Forecast/blob/main/Demand%20Forecast%20Modeling%20Approaches.ipynb), I experimented with a variety of techniques, including Random Forest, CatBoost, and neural networks utilizing TensorFlow, for both the regression and classification problems.

## Results

These are some of the results I achieved during this project:

<a href="https://imgbb.com/"><img src="https://i.ibb.co/nsHS3Pf/nnReg.png"  border="0"></a> "Regression with tensorflow neural networks"


<a href="https://imgbb.com/"><img src="https://i.ibb.co/tM7181Q/catboostcls.png" alt="catboostcls" border="0"></a> "CatBoost classifier"

## Visualization

Data visualization is a fantastic way to present data in a way that is easy for the human mind to comprehend. One of the key goals of data visualization is to make it simpler to spot patterns, trends and outliers in large datasets. By utilizing time series visualization and analytics, forecasts can be generated and the data can be better understood. Here are some of the examples:

<a href="https://ibb.co/dbrWndZ"><img src="https://i.ibb.co/B4tz8Xk/Vis3.png" alt="Vis3" border="0"></a>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/jMScr9J/Vis2.png" alt="Vis2" border="0"></a>
