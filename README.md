# Use of Data Science methods

## Predicting rainfall the next day

Example use of basic machine learning classifiers to predict whether there will be rain the following day, using a rainfall dataset from the Australian Government's Bureau of Meteorology.

After cleaning the data, different classification algorithms as well as accuracy metrics are compared in ther performance to classify the data.

#### **Notebooks**

Contained in the notebook "rainfallPrediction".

Libraries:

- Sklearn
- Numpy
- Pandas

Classification algorithms used to build the models:

1.  Linear Regression
2.  KNN
3.  Decision Trees
4.  Logistic Regression
5.  SVM

The results are reported as the accuracy of each classifier, using the following metrics when these are applicable:

1. Accuracy Score
2. Jaccard Index
3. F1-Score
4. LogLoss
5. Mean Absolute Error
6. Mean Squared Error
7. R2-Score

## Predicting Falcon 9 landing success

Predicting if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch.

This project serves as a demostration in the use of different Data Science tools for acquiring and manipulating data.

#### **Notebooks**

1. "falcon9-GetRequest".

API get request, html parsing and data wrangling.

Libraries:

- Requests
- Pandas

2. "falcon9-WebScraping".

API get request and html parsing and search.

Libraries:

- BeautifulSoup
- Requests
- Pandas

3. "falcon9-DataWrangling".

Exploratory Data Analysis and label creation to train a classification algorithm.

Libraries:

- Numpy
- Pandas

4. "falcon9-EDA-SQL"

Exploratory Data Analysis using SQL

Libraries:

- ipython-sql
- sqlalchemy

5. "falcon9-EDA-visualization"

Exploratory Data Analysis and visualization.

Libraries:

- Numpy
- Pandas
- Matplotlib
- Seaborn

6. "falcon9-Folium-Satellite"

Using Folium to explore satellite data.

Libraries:

- Pandas
- Folium

7.  "falcon9-Dash-plotly"

Using plotly Dash to create a dashboard.

Libraries:

- Pandas
- Dash
- Plotly.express

8. "falcon9-Prediction"

Use of SVM, Classification Trees and Logistic Regression to predict if a rocket launch will be successful.

Libraries:

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Sklearn
