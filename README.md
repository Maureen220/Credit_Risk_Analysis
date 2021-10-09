# Credit Risk Analysis

## **Overview of Analysis:**
The purpose of this analysis was to apply various machine learning techniques to determine credit risk in a credit card dataset from LendingClub. This project used the imbalanced-learn and scikit-learn libraries to apply several algorithms to the dataset to predict the best outcome for the client. 

## **Results:**
Please observe the following results from the tested algorithms: 

### 1. Naive Random Oversampling:

![random_oversampling.png](Resources/random_oversampling.png)
<br>
The accuracy score for Random Oversampling sits at 64%, with a precision of 99%, a sensitivity of 60%, and an F1 score of 75%. 
<br></br>

### 2. SMOTE Oversampling:

![SMOTE_oversampling.png](Resources/SMOTE_oversampling.png)
<br>
The accuracy score for SMOTE Oversampling sits at 66%, with a precision of 99%, a sensitivity of 69%, and an F1 score of 81%. 
<br></br>

### 3. Undersampling:

![random_undersampling.png](Resources/random_undersampling.png)
<br>
The accuracy score for Random Undersampling sits at 60%, with a precision of 99%, a sensitivity of 57%, and an F1 score of 72%. 
<br></br>

### 4. SMOTEENN (Combination sampling):

![SMOTEEN_combo.png](Resources/SMOTEEN_combo.png)
<br>
The accuracy score for SMOTEENN sits at 66%, with a precision of 99%, a sensitivity of 58%, and an F1 score of 73%. 
<br></br>

### 5. Balanced Random Forest Classifier:

![balanced_rf.png](Resources/balanced_rf.png)
<br>
The accuracy score for Balanced Random Forest Classifier sits at 78%, with a precision of 99%, a sensitivity of 87%, and an F1 score of 93%. 
<br></br>

### 6. Easy Ensemble AdaBoost Classifier:

![easy_ensemble_classifier.png](Resources/easy_ensemble_classifier.png)
<br>
The accuracy score for Easy Ensemble AdaBoost Classifier sits at 93%, with a precision of 99%, a sensitivity of 94%, and an F1 score of 97%. 
<br></br>

## **Summary:**
The results above show a clear winner in the algorithms. The Easy Ensemble AdaBoost Classifier achieved the high results on accuracy, precision, sensitivity, and F1 score. By combining multiple weak classifiers and giving the weight to create a strong classifier, the adaptive boosting can be more accurate in its predictions. It would be advisable to use this algorithm for future predictions of credit risk.
