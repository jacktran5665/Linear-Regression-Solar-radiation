# Linear-Regression-Solar-radiation-OBJECTIVES:
Implementing ML for linear regression to predict solar radiation levels in the (coming years) using databases.

Solar Radiation Datasets:

https://nsrdb.nrel.gov/data-sets/international-data

https://www.kaggle.com/datasets/dronio/SolarEnergy/data

https://www.kaggle.com/datasets/ibrahimkiziloklu/solar-radiation-dataset

https://www.kaggle.com/datasets/fuarresvij/uv-index-in-usa/data


Skin Cancer Datasets:

https://www.kaggle.com/datasets/farjanakabirsamanta/skin-cancer-dataset

https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000/data


## Project Approach

### 1. Understanding the Dataset
  - Examine data structure (columns, types, ...).
  - Identify key factors affecting the solar radiation (temperature, humidity, ...).
  - Detect patterns based on time or location.

### 2. Data Preprocessing
  - Handle any missing data (fill or remove).
  - Handle any extreme values (only handle if it significantly affect the model)
  - Adjust data if needed (if features have different ranges)
  - Change categorical data into a usable format (if necessary).

### 3. Exploring Relationships for the Model 
  - Use graphs to check how features are related to solar radiation. 
  - See if the data is simple enough for a linear model to work. 
  - Check if any similarity in datasets and fix it if needed.

### 4. Splitting Data for Training and Testing
  - Split the data into training and testing sets.
  - Make sure the testing set is separate from the training data to avoid bias. *(Might be imporant)*
  - Ensure the test data represents real-world situations you want to predict. (TBD - what kind of prediction is doable?)

