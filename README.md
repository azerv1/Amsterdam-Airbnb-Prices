#Airbnb Amsterdam Price Prediction and Data Visualization#
##Overview##
##This project aims to analyze and visualize Airbnb listings from Amsterdam. It explores various features like room type, distance from city center, guest satisfaction, and others to understand their impact on the listing price. Finally, a predictive model is developed using TensorFlow to estimate the listing price based on these features.##

###Table of Contents
###Installation
###Data Preparation
###Data Visualization
###Model Building
###Usage
###Credits

###Data Preparation
The dataset includes information like:

Room type
Distance from city center
Guest satisfaction
Number of bedrooms
Whether the host is a superhost
And many others
Data is cleaned and preprocessed for further analysis. Categorical values are encoded, and numerical features are scaled.

###Data Visualization
Various visualizations are created to understand the data better:

Pie chart for room capacity
Scatter plot for distance vs. price
Correlation heatmaps
And others
###Model Building
A neural network model is created using TensorFlow's Keras API to predict the listing price. The model is trained on 80% of the data, and its performance is evaluated using Mean Squared Error (MSE).

###Usage
To run the project:

Clone the repository.
Install the required packages.
Run the Jupyter Notebook or Python script containing the code.
###Credits
The dataset used in this project is based on the work "Determinants of Airbnb prices in European cities: A spatial econometrics approach" by Gyódi, Kristóf, & Nawaro, Łukasz. The dataset is available on Zenodo: Data set.
