# Cancer Classification
This notebook aims to classify breast tumors as benign or malignant using the Random Forest algorithm. The dataset used was obtained from Kaggle and contains information about characteristics of the scanned breast tissue of patients.

## Required Libraries
- pandas
- numpy
- imblearn
- sklearn

## Data set
The dataset used was obtained from Kaggle (https://www.kaggle.com/datasets/erdemtaha/cancer-data). It contains information about characteristics of breast tissue scanned from patients. There are 569 observations and 32 variables in the dataset. The target variable is the diagnosis column, which indicates whether the tumor is malignant (M) or benign (B).

## Data pre-processing
Data was loaded using the pandas library and missing values were removed. Categorical variables were coded as numerical variables and the target variable diagnosis was transformed into a binary value 1 for malignant and 0 for benign.

## Exploratory Data Analysis
An exploratory data analysis was performed to better understand the characteristics of the dataset. Histograms and scatterplots were plotted to understand the distributions of variables and their correlations.

## Modeling
The dataset was divided into training and test sets. The Random Forest algorithm was used to train the model and performance was evaluated using metrics such as accuracy, precision, recall and F1-score. In addition, a confusion matrix was created to better understand the results.

## Conclusion
The Random Forest model performed well in classifying breast tumors as benign or malignant. Precision, recall and F1-score were above 90%, indicating a good generalizability of the model. It is important to emphasize that the early detection of malignant tumors is fundamental for the effective treatment of the disease.
