**Which model had the best balanced accuracy score?**  
The Balanced Random Forrest Classifier had the best Balanced Accuracy Score at 0.75.

**Which model had the best recall score?**  
The Easy Ensemble Classifier has the best recall score at 0.94.  

**Which model had the best geometric mean score?**  
The Balanced Random Forrest Classifier has the best geometric mean at 0.74.

    
      
      
**Balanced Random Forrest Classifier**

Balanced Accuracy: 0.7515444247885967


                      pre       rec       spe        f1       geo       iba       sup

     high_risk       0.03      0.62      0.88      0.06      0.74      0.53       101
      low_risk       1.00      0.88      0.62      0.93      0.74      0.56     17104

      avg / total       0.99      0.88      0.63      0.93      0.74      0.56     17205   

[(0.06607490072728682, 'total_rec_prncp'),
 (0.06356072282512583, 'total_rec_int'),
 (0.06313117434543672, 'total_pymnt'),
 (0.060730609428838296, 'total_pymnt_inv'),
 (0.05399266686407467, 'last_pymnt_amnt'),
 (0.03353780574781485, 'int_rate'),
 (0.032277471900396926, 'month_num'),
 (0.02038661655587231, 'mths_since_recent_inq'),
 (0.02022237823990287, 'dti'),
 (0.01817643945661585, 'installment')]
 
 **Easy Ensemble Classifier**
 
 Balanced Accuracy: 0.5248717224388482
 
                   pre       rec       spe        f1       geo       iba       sup

     high_risk       0.01      0.11      0.94      0.02      0.32      0.09       101
      low_risk       0.99      0.94      0.11      0.97      0.32      0.11     17104

    avg / total       0.99      0.94      0.11      0.96      0.32      0.11     17205
