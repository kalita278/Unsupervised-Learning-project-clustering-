# Unsupervised-Learning-project-clustering-

**DOMAIN:** Automobile

**CONTEXT:** The data concerns city-cycle fuel consumption in miles per gallon to be predicted in terms of 3 multivalued discrete and 5
continuous attributes.

**DATA DESCRIPTION:**

1. cylinders: multi-valued discrete
2. acceleration: continuous
3. displacement: continuous 
4. model year: multi-valued discrete
5. horsepower: continuous
6.  origin: multi-valued discrete
7.  weight: continuous
8.  car name: string (unique for each instance)
9.  mpg: continuous 


**PROJECT OBJECTIVE:** To understand K-means Clustering by applying on the Car Dataset to segment the cars into various categories.

**DATA EXPLORATION AND DATA CLEANING:**

Combined the two files to create a single file with all the relevant variables and perform the necessary data quality checks and cleaning. In data cleaning, identified the missing values/unexpected values in the dataset and since the number of missing values is very less, replaced the missing values with median. Also make sure that the data types of the variables are appropriate as required for our analysis (Here, converted all the categorical variable data types to category and continuous variable data types to int or float).

**DATA ANALYSIS:**

Checked the distribution of data for the continuous and categorical variables. Performed uni-variate, bivariate, and multivariate analysis of the dataset, for example, 5-point summary of the continuous variable, pair plot, correlation matrix plot, scatter plot and box plot to detect outlier.

**DATA PREPROCESSING:**

Here, Scaled the variable/feature using standard scaler.

**CLUSTERING:**

Used k-Means clustering to group the cars. Here, used elbow method to find out the optimal number of clusters.
