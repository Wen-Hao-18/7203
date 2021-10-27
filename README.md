# Cell communication analysis of  E.coil based on four Basic classification algorithms
* author:Wang Wenhao(s4603994)
* date:2020.10.27
* libraries in main.py
 1. numpy,pandas (used for data input)
 2. sklearn 
   * SimpleImputer (for imputation)
   * KNeighborsClassifier ( After GridSearchCV's search, KNN has the best performance of 0.807 F1 score)
   * cross_val_score (cv for calculating)
   * StandardScaler (for data preprocessing)
   * LocalOutlierFactor (for anormal points detection)
 3. csv (used for result output as a csv file)

## main.py
* model_propessing(The function that using the optimal KNN model to train Ecoli.csv, predict Ecoli_test.csv and show the f1 and acc for the train set)
* csv_output(output the prediction as the csv file and combine the f1 and acc of the train set in cv)
