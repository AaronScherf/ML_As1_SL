Readme for replication of Supervised Learning analysis of algorithm performance across balanced and imbalanced data
Aaron Scherf
ascherf3

The Jupyter Notebook (https://github.com/AaronScherf/ML_As1_SL/blob/main/ML_As1_SL.ipynb) contained in the project repository on GitHub is self contained, in that it imports all data and libraries needed to reproduce the results.

Both the original source data and cleaned versions used for testing are also contained in the repository here: https://github.com/AaronScherf/ML_As1_SL/tree/main
The clean housing features can be found at: https://raw.githubusercontent.com/AaronScherf/ML_As1_SL/main/X_housing.csv
The housing target array is: https://raw.githubusercontent.com/AaronScherf/ML_As1_SL/main/y_housing.csv
The bankruptcy data is combined in one csv here: https://raw.githubusercontent.com/AaronScherf/ML_As1_SL/main/data.csv

The notebook contains all further processing, such as the categorization of the housing labels and SMOTE oversampling of the bankruptcy data.

The libraries required to implement the notebook are all available on a standard Google Colab system, which was used to execute the notebook. They include:
- pandas
- numpy
- matplotlib
- yellowbrick
- seaborn
- sklearn
- geopy
- imblearn

The notebook uses a random seed of 42 for all available random number generator inputs, to improve reproducibility.

The notebook can be executed with a "Run all" command to return all of the plots and descriptions used for the report.
