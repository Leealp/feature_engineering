# feature_engineering
Here we're using the technique of Feature Scaling to transform features in the dataset to the same scale

TITLE: Feature Scaling

DESCRIPTION

What is feature scaling?

It is a data preprocessing technique that consists in normalizing/standardizing the range of features in a dataset and transforming their to a similar scale.

Real-world datasets often contain features that are varying in degrees of magnitude, range, and units. Therefore, in order for machine learning models to interpret these features on the same scale, we need to perform feature scaling.

What’s the difference between Normalization and Standardization?

Normalization and Standardization are the two very popular methods used for feature scaling.

Normalization refers to re-scaling the values to fit into a range of [0,1].
Normalization is useful when all parameters need to have an identical positive scale however the outliers from the data set are lost.

Standardization refers to re-scaling data to have a mean of 0 and a standard deviation 
of 1 (Unit variance).

In this problem we'll use the StandardScaler function (a technique of normalization) and the MinMaxScaler function (a technique of standardization) to transform the features in the provided dataset to the same scale.

LIBRARIES

    Numpy
    Pandas
    sklearn
    

AUTHOR Alpha Ly
