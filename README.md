# We will work on handling the missing data as well as data normalization and standardization. The data can have missing values for number of reasons such as observations that were not collected or data corruption.
## Import and Install Libraries on Jupyter Notebook
* import numpy as np
* import pandas as pd
* from mlxtend.preprocessing import Min.Max_Scaling, Standardize
* import seaborn as sns
* import matplotlib.pyplot as plt

### Read in data
* present first five observation
* Working with missing data
* Take a look at the data
* Missing data are identified differntly
* We can calculate the percentage of all missing values
* Total number of missing values
* Percent of data that is missing

#### Drop missing values
* Create temporary dataframe
* Remove all the rows contain a missing values

##### Let look which columns were removed
* Create a temporary dataframe
* Remove all columns with at least one missing value

###### Filling in missing values automatically
* We use pandas fillna() function to in missing values in dataframe
* Create a temporary dataframe
* Replace all NA's with 0

###### Feature Scaling Recap
* Two types of features scaling : Standardization and Normalization
* From the countries dataset, visualise the "EG.ELC.ACCS.ZS" column using a histogram.
* Then, scale the column using the appropriate scaling method (normalisation or standardisaton).
* Visualize the data
* Visualize the normalized data
* Standardize the data
* Use subplot to compare the distributions
  
  
