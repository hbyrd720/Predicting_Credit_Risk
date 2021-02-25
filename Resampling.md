**Which model had the best balanced accuracy score?**

SMOTE had the best balanced accuracy score at 0.78

**Which model had the best recall score?**

SMOTE also had the best recall score at 0.80

**Which model had the best geometric mean score?**

SMOTE also had the best geometric mean scoree at 0.78
  
  
  
**Naive RandomOverSampler**

Balanced Accuracy: 0.7682118246904204

                      pre       rec       spe        f1       geo       iba       sup

      high_risk       0.02      0.74      0.79      0.04      0.77      0.59       101
      low_risk       1.00      0.79      0.74      0.88      0.77      0.59     17104

      avg / total       0.99      0.79      0.74      0.88      0.77      0.59     17205

**SMOTE**

Balanced Accuracy: 0.7763487088886625

                       pre       rec       spe        f1       geo       iba       sup

       high_risk       0.02      0.75      0.80      0.04      0.78      0.60       101
       low_risk       1.00      0.80      0.75      0.89      0.78      0.61     17104
   
       avg / total       0.99      0.80      0.75      0.88      0.78      0.60     17205

**Undersampling (ClusterCentroids)**

Balanced Accuracy: 0.7495736623475258

                      pre       rec       spe        f1       geo       iba       sup

       high_risk       0.02      0.81      0.69      0.03      0.75      0.56       101
       low_risk       1.00      0.69      0.81      0.81      0.75      0.55     17104

     avg / total       0.99      0.69      0.81      0.81      0.75      0.55     17205


**SMOTTEEN**

Balanced Accuracy: 0.611206399522085

                      pre       rec       spe        f1       geo       iba       sup

     high_risk       0.01      0.86      0.36      0.02      0.56      0.33       101
     low_risk       1.00      0.36      0.86      0.53      0.56      0.30     17104

     avg / total       0.99      0.36      0.86      0.53      0.56      0.30     17205
