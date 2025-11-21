📘 README: 

Impact of Technology on GDP Growth Analysis


Project Overview

This project investigates the relationship between technology adoption and GDP growth across 120 countries using real-world economic indicators.
It was developed as a comprehensive practical demonstration of everything I have learnt in the world of data science — including data cleaning, exploratory analysis, visualization, statistical modelling, and interpretation of insights for real-world application.

The repository contains:
* A CSV dataset with GDP and technology-related variables.
* A Jupyter Notebook where the full analysis, modelling, and visualization are carried out.


Project Files
1. 120-countries_gdp_growth.csv
This dataset contains country-level metrics used for the analysis, such as:
* GDP growth rate
* Technology adoption indicators
* Broadband & mobile penetration
* Innovation indices
* Investment in technology
* Other socio-economic control variables
2. Impact_of_Technology_on_GDP_Growth.ipynb
This notebook includes:
* Data loading & cleaning
* Exploratory Data Analysis (EDA)
* Visualization of patterns and correlations
* Regression modelling (Linear Regression / Multivariate Regression)
* Interpretation of how tech variables influence GDP growth
* Policy-oriented insights



Objectives of the Analysis
The goals of this study are to:
* Determine how technological advancement affects a country’s GDP growth.
* Identify which technology metrics have the strongest economic impact.
* Build statistical models to quantify these relationships.
* Provide data-driven policy recommendations for enhancing economic growth through technology.



Technologies & Libraries Used
The notebook makes use of:
* Python 3
* Pandas – data cleaning & manipulation
* NumPy – numerical operations
* Matplotlib / Seaborn – visualizations
* Scikit-learn – regression models
* Jupyter Notebook – analysis environment


Key Steps in the Notebook


Loading and Inspecting the Data

Initial overview of dataset structure, data types, missing values, and summary statistics.

Data Cleaning

* Handling missing values
* Converting data types
* Feature normalization where necessary

Exploratory Data Analysis

* Distribution of GDP growth
* Correlation heatmaps
* Pairplot relationships between technology variables and GDP growth
* Insights into regional variation
* 
Regression Modelling

Regression techniques to quantify economic impact of technology:
* Simple Linear Regression
* Multivariate Regression
* Model evaluation using R², RMSE, and residual plots


Findings & Policy Recommendations
Interpretation of results:
* Which technological indicators significantly drive economic growth
* Strategic recommendations for policymakers
* How developing nations can accelerate tech-led growth


Expected Insights


By the end of the analysis, the notebook provides insights such as:
* Whether countries with higher digital adoption experience faster GDP growth
* The strength and direction of correlations between tech indicators and growth
* Predictive capability of technology metrics
* Actionable policy suggestions for governments

How to Run the Notebook
1. Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn jupyter
1. Launch Jupyter Notebook:

jupyter notebook
1. Open: Impact_of_Technology_on_GDP_Growth.ipynb
2. Ensure the dataset file is in the same directory:

120-countries_gdp_growth.csv



