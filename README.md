# Classification of lending data with imbalanced classes
---

This repository contains example iplementation of classification of data with imbalanced class. Credits and Loan data are used - two classes of default - high risk and low risk with low risk class being the minority class.  

Following techniques are demonstrated: 
* Resampling to make the blanaced samples with Naive Random Oversampling, SMOTE Oversampling, ClusterCentroids Undersampling, and Combination Sampling 
* Emsemble learning with Balanced Random Forest Classifier and Easy Ensemble Classifier


## How to run the notebooks <br>
Clone the entire repository - "imbalanced-classification"  into a local folder by issuing the following command from gitbash <br>
```
$git clone https://github.com/Roy-Tapas/imbalanced-classification.git
```
Stay in the same gitbash directory and open Jupyter lab by issuing the following command from gitbash: <br>
```
$jupyter lab
```

Implementations are in following two notebooks:
* credit_risk_resampling.ipynb
* credit_risk_ensemble.ipynb

## Important points to note 
Retain the folder structure as cloned from github.  
Hierarchy inside timeseries-analysis-japanese-yen should look like the following:
```
timeseries-analysis-japanese-yen 
        |---------------> README.md 
        |---------------> credit_risk_resampling.ipynb 
        |---------------> credit_risk_ensemble.ipynb 
        |---------------> Resources
                            |--------> lending_data.csv
                            |--------> LoanStats_2019Q1.csv 
                        
```



<hr style="border:2px solid blue"> </hr>

## Tapas Roy

**Email:** rtapask@gmail.com