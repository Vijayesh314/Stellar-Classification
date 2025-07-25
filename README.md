# Stellar-Classification

The project focuses on building a machine learning classification model to predict the type of star, such as main sequence, dwarfs, or giants, based on their physical characteristics. Using a dataset of 240 stars with features like temperature, luminosity, radius, absolute magnitude, color, and spectral class, I trained a Random Forest model in R to classify stars into one of six types.

Key Steps
* Cleaned and renamed features
* Dataset from Kaggle, no missing or duplicates
* Conducted Exploratory Data Analysis with univariate, bivariate, and multivariate visualizations
* Tuned the model using mtry parameter

Results
* Achieved high scoring metrics (precision, recall, accuracy, f1 score) ~ 98%
* Found that the stellar classification is correlated to the Hertzsprung–Russell diagram
* The model confirms a key astrophysics relationship
