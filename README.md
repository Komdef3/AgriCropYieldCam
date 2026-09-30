PROJECT OVERVIEWBackground
Agriculture is the backbone of many African economies and is the main source of livelihood for a large percentage of the population, especially in Cameroon. Most farming activities in the country, including crop yield estimation, are still done manually. Farmers make decisions based on personal experience, observation, and informal knowledge passed down over generations.
However, as climate conditions become less predictable and food demand continues to grow, these traditional methods are no longer reliable enough. Unpredictable rainfall, rising temperatures, and poor soil management have made it harder for farmers to estimate how much crop they will harvest. This often leads to poor planning, wastage of resources, food shortages, and financial hardship.
The field of data mining offers a practical solution. By using historical agricultural data and machine learning algorithms, it is possible to build a model that can predict crop yield with measurable accuracy. This project applies data mining techniques to real-world agricultural datasets to build, train, and compare several predictive models for crop yield estimation.
Problem Statement
In many parts of Africa, including Cameroon, crop yield estimation is still based on manual observation and guesswork. This makes it very difficult for farmers, agricultural agencies, and government policymakers to plan ahead. The absence of a data-driven tool means that decisions about food distribution, market pricing, and resource allocation are often made without accurate information.
As a result, smallholder farmers are frequently exposed to unexpected crop failures and economic losses. Agricultural bodies struggle to respond in time to food insecurity situations because they cannot predict when and where crop shortfalls will happen. This project addresses that gap by building a data mining model that takes in environmental and agronomic variables and outputs a predicted crop yield value.


Aim and Objectives
Aim: To develop a data mining model that accurately predicts crop yield based on environmental and agronomic input variables.

Objectives:
•	Collect and preprocess historical agricultural datasets from credible online sources.
•	Perform Exploratory Data Analysis (EDA) to identify key yield-influencing variables.
•	Apply and compare multiple data mining algorithms: Linear Regression, Decision Tree, Random Forest, and XGBoost.
•	Evaluate model performance using standard metrics: RMSE, MAE, and R-squared (R²).
•	Identify the most significant features that influence crop yield.
•	Build a prediction function that can accept real input values and return a yield estimate.

Data Sources
The datasets used in this project were obtained from four publicly available and credible sources, as shown in Table 1.1 below.

Source	Dataset	Data Provided
Kaggle / FAOSTAT (Zenodo)	df_yield_merged.csv	Crop type, rainfall, temperature, pesticide usage, yield (hg/ha)
FAOSTAT (UN FAO)	yield.csv, pesticides.csv, rainfall.csv, temp.csv	Country-level crop production data
UCI ML Repository	Crop_recommendation.csv	Soil NPK levels, temperature, humidity, rainfall, crop labels
World Bank	data.worldbank.org	Climate indicators and agricultural output by country

 
Methodology
CRISP-DM Framework
This project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework. CRISP-DM is a widely used methodology for data mining and machine learning projects. It provides a structured process that guides a project from data collection all the way to model deployment. The framework has six phases as described in Table 2.1 below.
2.2 Tools and Technologies
All data processing, analysis, and modelling in this project was done using Python. The tools and libraries used are listed in Table 2.2.

Tool / Library	Version	Purpose
Python	3.12	Primary programming language
Pandas	Latest	Data loading, cleaning, and manipulation
NumPy	Latest	Numerical operations and array handling
Matplotlib	Latest	Data visualisation and chart generation
Seaborn	Latest	Advanced statistical visualisations
Scikit-learn	Latest	Machine learning models, preprocessing, and evaluation
XGBoost	Latest	Gradient boosting regression model
Jupyter Notebook	Latest	Interactive environment for writing and running code
