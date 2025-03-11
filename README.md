# Linear-Regression-Solar-radiation
Implementing ML for Linear Regression that will predict where solar radiation level is at in the next few years given the databases.

Datasets:
https://nsrdb.nrel.gov/data-sets/international-data


Approach:
- I should be able to start by understanding the dataset and identifying the features that could influence solar radiation:

- Sub Look at the data to see what it contains (e.g., columns, types of information).
- Sub Find possible factors (like temperature or humidity) that might affect solar radiation.
- Sub Check if there are any patterns over time or by location.
  
- I should be able to preprocess the data to ensure it's ready for training, handling any missing values or outliers:
- Sub Check for missing data and decide how to fix it (e.g., fill it in or remove it).
- Sub Find and deal with any extreme values that might mess with the model.
- Sub Scale or adjust data if needed, especially if different features have different ranges.
- Sub Convert any categorical data (like labels) into a usable format if needed.

- I should be able to explore relationships between variables and check if a linear model is appropriate:
- Sub Use graphs to see how the features are related to solar radiation.
- Sub Check if the data looks linear or straight enough for a linear model to work.
- Sub See if any features are too similar to each other (multicollinearity) and adjust if necessary.
  
- I should be able to split the data into training and testing sets to evaluate the model's performance:
- Sub Split the data into a training set (for building the model) and a testing set (for checking its accuracy).
- Sub Make sure the testing set is separate from the training data to avoid bias.
- Sub Check that the testing data truly represents the real-world situation you want to predict.

