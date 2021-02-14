# Machine-Learning-Project
Flight Delays of London Heathrow Airport Prediction
In order to have the machine trained, you need to build a dataset with the FlightRadar24_scrapper (at least 2-3 weeks data). 
Data preparation is performed in the scrapper, but data cleansing and feature engineering is perfomed in the machine learning file.
Scrapper may have duplicate values which are removed in the machine learning script.
Example dataset is cocluded in the repository which was used to train-test and valiate the model.


Libraries used for FlightRadar24_scrapper.ipynb and London_Heathrow_Dep_Delays.ipynb :
* numpy       : 1.19.2
* pandas      : 1.1.1
* tensorflow  : 2.0.0
* tensorboard : 2.0.0
* seaborn     : 0.11.0
* matplotlib  : 3.3.2
* xgboost     : 0.90
* plotly      : 4.12.0
* FreeProxy   : 1.0.2
* sklearn     : 0.23.2

Python Version: 3.7.1

files: 
* [FlightRadar24_scrapper](https://nbviewer.jupyter.org/github/stefand-ml/Machine-Learning-Project/blob/main/FlightRadar24_scrapper.ipynb)
* [London_Heathrow_Dep_Delays](https://nbviewer.jupyter.org/github/stefand-ml/Machine-Learning-Project/blob/main/London_Heathrow_Dep_Delays.ipynb)
