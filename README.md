<a name="top"></a>


# :rocket: SC1015 - Predicting HDB resale flat prices in Singapore
This repository contains the project files for the our mini project which aims to predict HDB resale flat prices in Singapore, based on this dataset: [Resale Flat Prices from January 2017 onwards](https://beta.data.gov.sg/collections/189/datasets/d_8b84c4ee58e3cfc0ece0d773c8ca6abc/view)
We will also be using the HDB Resale Price Index (RPI) to predict future prices based on past resale transaction data. [RPI](https://www.hdb.gov.sg/residential/selling-a-flat/overview/resale-statistics)

### Contributors
  - [@ajunhoa](https://github.com/ajunhoa) - *EDA, Data Cleaning, Pre-processing, Models Implementation, Hyper Parameter Tuning, Slides* -
  - [@jodylalala](https://github.com/jodylalala)- *Linear Regression, Gradient Boost Regressor, Readme, Slides* -
  - [@winstontai](https://github.com/winstontai)- *EDA, Hyper Parameter Tuning, Sarimax, SVR, Script, Slides* -

    ---

## Table of Contents:
#### Introduction to our Project
- [Problem Statement](#prob)
- [Datasets](#datasets)
#### Implementation
- [Models we used](#models)
- [Steps we took](#steps)
- [Improvements Made](#Improvements)
- [Data Driven Insights, Conclusion and Recommendations](#conclude)
- [What we've learnt](#learnt)
#### Files Included
- [Notebook](/main.ipynb)
- [Dataset](/data/ResaleflatpricesbasedonregistrationdatefromJan2017onwards.csv)
- [Legend of Dataset](/images/legend.png)
- [Image of Sample Dataset](/images/sample_data.png)
#### Other Relevant Information
- [Setting Up the Notebook](#config)
- [References](#ref)
---
## Introduction
<a name="prob"></a>



#### Problem Statement
Through this project, we aim to solve a common problem that is faced by Singaporean Couples who intend to purchase a Resale flat from the HDB open market. 



Our success metric is determined through accuracy of predicted HDB resale flat price

Through our project, we hope to provide a platform for potential homeowners to seek their dream home. 


<a name="datasets"></a>


#### Datasets: 
[Resale Flat Prices from January 2017 onwards](https://beta.data.gov.sg/collections/189/datasets/d_8b84c4ee58e3cfc0ece0d773c8ca6abc/view)<br>

#### Sample Data: <br>![sample_data](/images/sample_data.png)<br>
#### Dataset Legend: <br>![dataset](/images/legend.png)

<a name="models"></a>
---

## Implementation


### Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Ridge Regression
- Lasso Regression
- ElasticNet Regression
- SVR
- KNN Regression
- XGBoost Regression
- LightGBM Regression
- CatBoost Regression

<a name="steps"></a>


### Steps we took
1) Exploratory Data Analysis to analyse our dataset
2) Data Cleaning to remove any dirty or null data
3) Pre-processing e.g categorical values to numerical values for model training
4) Feature Engineering to select features that are impactful to model prediction
5) Train with regression models
6) Hyper Parameter Tune models to improve accuracy

<a name="Improvements"></a>


### Improvements made


<a name="conclude"></a>


### Data Driven Insights, Conclusion & Recommendations


#### Limitations of this model
Purchasing a flat in Singapore often include factors that are intangible. These factors are often directly related to the buyer of the flat. 
Some factors could include:
- Distance from a Primary School that a parent is intending to enroll their child in, with prices near famous Primary schools increasing due to the demand. 
- Distance from an MRT, with prices increasing significantly the nearer a flat is to the MRT. 


<a name="learnt"></a>


### What we've learnt

- Usage of other regression models & SARIMAX
- Exploring data with Plotly
- Tuning our own models
- Collaborating in Github
- Using different python packages
- Data wrangling with encoders

<a name="config"></a>
---

## Other Relevant Information


#### Configuration

How to use our notebook:

open your terminal and run this line:

    pip install -r requirements.txt




<a name="slidesused"></a>


---
#### Slides used in our presentation video

- [Our slides ](https://www.canva.com/design/DAGA-lWt5DI/YJIK_vCaoKLj0cnpRK-LaA/view?utm_content=DAGA-lWt5DI&utm_campaign=designshare&utm_medium=link&utm_source=editor) 




<a name="ref"></a>


---
#### References

  - Readme template from: [Billie Thompson](a-good-readme-template) 
  - [HDB Resale Transaction Price Checker](https://services2.hdb.gov.sg/webapp/BB33RTIS/BB33PReslTrans.jsp)
  - [PropertyGuru](https://oats.com.sg/wp-content/uploads/2020/05/oats-propertyguru-logo.png)
  - [99.c0](https://www.gawcapital.com/portfolio/99-group/)
  - [srx](https://www.srx.com.sg/)



Thank you for reading till the end!

### [Scroll to top ^](#top) 
