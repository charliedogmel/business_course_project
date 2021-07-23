# Expanding the Community

### Bringing more Community Shared Solar to Underserved Communities

#### Melissa Cooper

## Abstract

The goal of this project is a proposal to GRID Alternatives to use data science to predict the low-income areas most suitable for and most amenable to participating in community solar projects. I explored data from Google's Project Sunroof and Stanford's DeepSolar using spreadsheets and Tableau to find feature relationships to use in a future machine learning algorithm.

## Design

Solar photovoltaic (PV) installations are growing rapidly, yet the people who would benefit most from lower energy bills and cleaner air are often unable to adopt solar systems. One in three U.S. households experience energy insecurity. Community solar participation or no-cost solar systems can help reduce this burden. GRID Alternatives already addresses this by partnering with utilities and community groups to develop community shared solar arrays to benefit those households. GRID also provides no-cost solar systems to single-family homeowners who qualify as low-income. This proposal seeks to help GRID Alternatives better identify the communities with the greatest need and potential for solar adoption. It will use data science to quickly predict which households and areas to target and which rooftops qualify for installations.

# Data

Google's Project Sunroof uses satellite images to estimate the solar potential of rooftops of each census tract in the contiguous United States. It also creates a list of each rooftop's solar panel capacity.

Stanford's DeepSolar is a deep learning framework analyzing satellite imagery to identify the GPS locations and sizes of solar photovoltaic panels. It is the first comprehensive, publicly available database of existing solar installations.

Data processing involved merging the two datasets and using features from both to extract insights.

# Algorithms

There are several potential data science solution paths. An unsupervised machine learning algorithm using clustering shows the most potential. Using DBSCAN, K-Means, or KNN, the algorithm will group clusters of census tracts that are alike with features that influence solar adoption. Using the cluster with the highest average of existing solar systems, identifying outliers with low solar adoption will be the areas to target because they have features that indicate otherwise.

# Tools

* EDA & Plotting:  Tableau & LibreOffice Calc (open-source Excel for Linux)

# Communication

Slides, presentation, and this writeup
