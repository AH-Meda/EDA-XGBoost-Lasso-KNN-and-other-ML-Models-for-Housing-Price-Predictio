# EDA-XGBoost-KNN-and-other-ML-Models-for-Housing-Price-Predictions

**`Project Description`**
Accurately predicting housing prices is essential in the dynamic real estate market, benefiting buyers, sellers, and investors. Reliable predictions can guide investment decisions, inform pricing strategies, and enhance market stability. By using advanced data analytics and machine learning techniques, we can gain significant insights into market dynamics and accurately forecast future sales trends. In this project, we employ various machine learning ALgorithms to predict house prices based on several property attributes, such as location, size, condition, and other relevant factors.

We will use a housing dataset provided by De Cock (2011), which details residential sales in Ames, Iowa, from 2006 to 2010. This dataset includes 79 features describing the house and its corrosponding price. 

**`Mian Project Tasks`**

**`I. Data Loading, Cleaning and Preprocessing`**
- Load the dataset from Kaggle using the Kaggle API, importing it into the working directory.
- Develop an overview of the dataset, detailing data types, structure, and summary statistics to identify errors, inconsistencies, and patterns.
- Handle missing values and duplicates within the dataset.
- Ensure data schema consistency by addressing irregularities in data entries.
- Inspect and treat any outliers in the data.

**`II. Explanotary Data Analysis`**

During EDA, we will visualize the features and target data using histograms, box plots, scatterplots, and density plots. This process helps understand data distribution and central tendency, providing insights for feature engineering. Our analysis will cover univariate, bivariate, multivariate, and time series analyses..

**`II. Feature Engineering`**
- Identify relevant features based on EDA, using domain knowledge or feature ranking algorithms.
- Create new features from existing ones if necessary.
- Encode and scale features, converting categorical features into numerical representations and scaling them for improved algorithm performance.

**`IV. Machine Learning Implementation`**
- Select Candidate Machine Learning algorithms- 
- Make Base evaluation and identify better performing and/promosing models
- Hyperparatemer tuning of the models- we fine-tune models hyperparameters to further improve  its performance.
Finally, we validate the selected model on test data, indentify important features for the model and save model for future use.
