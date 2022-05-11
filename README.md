# Credit Risk Analysis

## Overview
The aim of this project is to utilize machine learning models in assessing an individual's credit risk. We are going to use different machine learning methods in determining credit risk and asses which mmodel might suit our analysis best. Here is the list of machine learning models to be used:

**- Oversampling (RandomOverSampler) & SMOTE**
**- Undersampling (ClusterCentroids)
**- Combo sampling approach (SMOTEENN)**
**- BalancedRandomForestClassifer & EasyEnsembleClassifer**

For each model, we are determine its balanced accuracy score, precision, recall and F1 score. We will then compare and contrast to see which might be best suitable for credit risk assesment.

## Results

<div align=center>
<img src = https://raw.githubusercontent.com/RobC30/Credit_Risk_Analysis/main/Resources/images/over.png>
</div>


<br>

### RandomOverSampler

Using the RandomOverSampler model, we can attain an balanced accuracy score of 65%. <br>
Other statistics as follows:

- Precision - 1% (High-Risk) & almost 100% (Low Risk)
- Recall/Sensitivity - 71% (High-Risk) & 60% (Low-Risk)
- F1 Score - 2% (High-Risk) & 75% (Low-Risk)
____________________________________________________

<div align=center>
<img src = https://raw.githubusercontent.com/RobC30/Credit_Risk_Analysis/main/Resources/images/smote.png>
</div>
<br>

### SMOTE

Using the SMOTE model, we can attain an balanced accuracy score of 65%. <br>
Other statistics as follows:

- Precision - 1% (High- Risk) & almost 100% (Low Risk)
- Recall/Sensitivity - 71% (High-Risk) & 69% (Low-Risk)
- F1 Score - 2% (High-Risk) & 82% (Low-Risk)
____________________________________________________

<div align=center>
<img src = https://raw.githubusercontent.com/RobC30/Credit_Risk_Analysis/main/Resources/images/under.png>
</div>
<br>

### ClusterCentroids

Using the ClusterCentroids model, we can attain an balanced accuracy score of 54%. <br>
Other statistics as follows:

- Precision - 1% (High- Risk) & almost 100% (Low Risk)
- Recall/Sensitivity - 69% (High-Risk) & 40% (Low-Risk)
- F1 Score - 1% (High-Risk) & 57% (Low-Risk)
____________________________________________________

<div align=center>
<img src = https://raw.githubusercontent.com/RobC30/Credit_Risk_Analysis/main/Resources/images/combo.png>
</div>
<br>

### SMOTEENN

Using the SMOTEENN model, we can attain an balanced accuracy score of 64%. <br>
Other statistics as follows:

- Precision - 1% (High- Risk) & almost 100% (Low Risk)
- Recall/Sensitivity - 72% (High-Risk) & 58% (Low-Risk)
- F1 Score - 2% (High-Risk) & 73% (Low-Risk)
____________________________________________________

<div align=center>
<img src = https://raw.githubusercontent.com/RobC30/Credit_Risk_Analysis/main/Resources/images/forest.png>
</div>
<br>

### BalancedRandomForestClassifier

Using the BalancedRandomForestClassifier model, we can attain an balanced accuracy score of 78%. <br>
Other statistics as follows:

- Precision - 4% (High- Risk) & almost 100% (Low Risk)
- Recall/Sensitivity - 67% (High-Risk) & 91% (Low-Risk)
- F1 Score - 7% (High-Risk) & 95% (Low-Risk)
____________________________________________________

<div align=center>
<img src = https://raw.githubusercontent.com/RobC30/Credit_Risk_Analysis/main/Resources/images/easy.png>
</div>
<br>

### EasyEnsembleClassifier

Using the EasyEnsembleClassifier model, we can attain an balanced accuracy score of 92%. <br>
Other statistics as follows:

- Precision - 7% (High- Risk) & almost 100% (Low Risk)
- Recall/Sensitivity - 91% (High-Risk) & 94% (Low-Risk)
- F1 Score - 14% (High-Risk) & 97% (Low-Risk)
____________________________________________________

## Summary
For our credit risk analysis, our objective is to determine if a loan would be high-risk for a bank. We will mainly look at these 3 statistics, High-Risk recall rate, Low-Risk recall rate & accuracy score. Considering all these, if we are to use the EasyEnsembleClassifer model for our analysis, this will be the best prediction tool for credit risks. 
