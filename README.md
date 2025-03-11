# Linear-Regression-Solar-radiation
Implementing ML for Linear Regression that will predict where solar radiation level is at in the next few years given the databases.

Datasets:
https://nsrdb.nrel.gov/data-sets/international-data

## Project Approach

### 1. Understanding the Dataset
- **I should be able to start by understanding the dataset and finding features that might affect solar radiation:**
  - Look at the data to see what it has (e.g., columns, types of information).
  - Find factors (like temperature or humidity) that could affect solar radiation.
  - See if there are any patterns based on time or location.

### 2. Data Preprocessing
- **I should be able to preprocess the data to make sure it's ready for training, handling missing values or outliers:**
  - Check for missing data and decide how to fix it (e.g., fill it in or remove it).
  - Find any extreme values that could mess with the model and handle them.
  - Adjust the data if needed, especially if features have different ranges.
  - Convert any categorical data (like labels) into a usable format if needed.

### 3. Exploring Relationships and Model Suitability
- **I should be able to explore relationships between variables and check if a linear model is right:**
  - Use graphs to see how the features are related to solar radiation.
  - Check if the data is straight enough for a linear model to work.
  - See if any features are too similar to each other (multicollinearity) and fix it if needed.

### 4. Splitting Data for Training and Testing
- **I should be able to split the data into training and testing sets to check the model's performance:**
  - Split the data into a training set (to build the model) and a testing set (to check its accuracy).
  - Make sure the testing set is separate from the training data to avoid bias.
  - Make sure the testing data represents the real-world situation you want to predict.

