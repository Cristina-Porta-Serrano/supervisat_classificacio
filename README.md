# supervisat_classificacio
M07 T01


## State of art

This dataset is the result of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines.

Dataset consists of 178 Italian wine samples. Each sample has 14 features: one is the cultivar's identifier, and the others are chemical attributes. The cultivar is a categorical variable that can take only 3 values: (Region) 1, (Region) 2, and (Region) 3. The chemical attributes are all numerical and continuous. This is a list of the 14 variables:

* *Cultivar's Identifier (target variable):*


  * Class Id (Type of wine)



* *Attributes (explanatory variables):*

  * Alcohol
  * Malic acid
  * Ash
  * Alcalinity of ash
  * Magnesium
  * Total phenols
  * Flavanoids
  * Nonflavanoid phenols
  * Proanthocyanins
  * Color intensity
  * Hue
  * OD280/OD315 of diluted wines
  * Proline


## Results

We have constructed our models using various classifiers such as Decision Tree, Logistic Regression Classifier and Support Vector Machine and we have tried to improve it using different feature engineering techniques. The results of the f1_score of the different models have been validated using Cross Validation. A result of 100% has been achieved with both Logistic Regression and Support Vector Machine. A table with the results has been created:

![taula F1 score](https://user-images.githubusercontent.com/104349352/179922661-169c7ef4-51fc-4baf-92cb-991ee67866d1.PNG)

I would choose the Logistic Regression model as the best one.

## Requirements

This notebook requires a Python 3.6 or newer version.

To run this notebook you must have installed the following libraries:

    pip install pandas
    pip install numpy
    pip install matplotlib
    pip install seaborn
    pip install scipy
    pip install -U scikit-learn
