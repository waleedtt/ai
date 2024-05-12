# AI Study
AI study

## Installation
```
virualenv env
source env/bin/activate

pip install numpy
pip install matplotlib
pip install pandas
pip install scikit-learn
```

## Data Preproccessing
* Importing Data

This process will import the data
```
dataset = pd.read_csv('Data.csv')
```
* Taking care of missing data - Mean the missing values

This process with add missing values
```
from sklearn.impute import SimpleImputer
imputer = SimpleImputer(missing_values=np.nan, strategy='mean')
```
* Encoding categorical data - OneHotEncoder

Categorical data is string values, we need to convert it into binary values
Like
Apple 00
Banana 01
Mango 10
```
ct = ColumnTransformer(transformers=[('encoder', OneHotEncoder(), [0])], remainder='passthrough')
```
* Splitting the dataset into the Training set and Test set

This process splits training set and test set
```
from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size = 0.2, random_state = 1)
```

* Feature Scaling

This process scales data to transforms the values of features or variables in a dataset to a similar scale. The purpose is to ensure that all features contribute equally to the model and to avoid the domination of features with larger value.

There are several common techniques for feature scaling, including standardization, normalization, and min-max scaling. These methods adjust the feature values while preserving their relative relationships and distributions.

[Link](https://www.analyticsvidhya.com/blog/2020/04/feature-scaling-machine-learning-normalization-standardization/)

[Link1](https://www.geeksforgeeks.org/ml-feature-scaling-part-2/)
```
from sklearn.preprocessing import StandardScaler
sc = StandardScaler()
X_train[:, 3:] = sc.fit_transform(X_train[:, 3:])
X_test[:, 3:] = sc.transform(X_test[:, 3:])
```