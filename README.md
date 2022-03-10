# breast_cancer_prediction-LogisticR

* Structured Dataset: Breast Cancer Wisconsin, UCI Machine Learning Repository(https://archive.ics.uci.edu/ml/index.php)
* Used Model: Logistic Regression
* Specification: Unsupervised Learning, Classification

## Dataset Columns
```rb
column_names = ['Patient_ID','Clump_Thickness','Uniformity_of_CellSize','Uniformity_of_CellShape','Marginal_Adhesion','Single_Epithelial_Cell_Size','Bare_Nuclei','Bland_Chromatin','Normal_Nucleoli','Mitoses','Class']
```

## Hyperparameters
* learning_rate = 0.003
* batch_size = 30
* iter_num = 100000

## Results
* Train_acc: 0.967033
* Test_acc: 0.948905
