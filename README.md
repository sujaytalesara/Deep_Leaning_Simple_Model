# pima-diabetes
A simple implemantation of basic deep learning model.

# Keras
Keras is a powerful and easy-to-use free open source Python library for developing and evaluating deep learning models.
# Steps 
The steps you are going to cover in this tutorial are as follows:
1. Load Data.
2. Define Keras Model.
3. Compile Keras Model.
4. Fit Keras Model.
5. Evaluate Keras Model.

# Dataset Information
The variables can be summarized as follows:

## Input Variables (X):
    Number of times pregnant
    Plasma glucose concentration a 2 hours in an oral glucose tolerance test
    Diastolic blood pressure (mm Hg)
    Triceps skin fold thickness (mm)
    2-Hour serum insulin (mu U/ml)
    Body mass index (weight in kg/(height in m)^2)
    Diabetes pedigree function
    Age (years)
    
## Output Variables (y):
    Class variable (0 or 1)
    
# Model Details :
We use a Sequential Model for modelling with loss funtion as Binary Cross Entropy, optimizer as Adam.
