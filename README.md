# Hurricane Prediction Model
 Predicting Intensity of Hurricane

This script analyze Risk-Score calculated by USC-ANRG team to determine if the Risk-Score of different regions in LA county is trending up or down.

Instructions for running the following code:
=================================================================================
Note: These files are developed and tested in Python 3.7.6.

The following packages are required to run the codes:
-jupyter noteboook
-numpy
-scipy
-pandas
-sklearn
-datetime
-matplotlib
-re
-timeit

=================================================================================
"RI Prdiction Model"

Required input files:
“Dataset_SHIPS_RII_ATL.csv"

=================================================================================
=============================     Results      ==================================
- Evaluation Table
- A table listing all different models, parameters, sampling methods, and features used to predict Hurricane Intensity
Column Description:
            - Normalized: Shows whether the feature data is normalized or not
            - Predictor Set: The name of the feature set used to predict hurricane intensity
            - ML Name: Types of machine learing algorithm used
            - Sampling Method: Shows which sampling method used
            - True Positive: Number of correctly predicted high-intensity hurricane
            - True Negative: Number of correctly predicted low-intensity hurricane
            - False Negative: Number of incorrectly predicted low-intensity hurricane
            - False Positive: Number of incorrectly predicted high-intensity hurricane
            - PSS: Peirce Skill Score (PSS)
            - FAR: False Alarm Ratio (FAR)
            - POD: Probability of Detection (POD)/True Positive Rate(TPR)/Recall/Sensitivity
            - F1: weighted average of precision and recall
            - Precision: Positive Predictive Value
            - Brier Score: a score function that measures the accuracy of probabilistic predictions




=================================================================================
================================= GitHub Repository =============================
We will also make the raw python scripts available via our GitHub repository: 
http://localhost:8888/tree/Guided%20Project/Hurricane-Prediction-Model


=================================================================================
================================= Contact Info ==================================
Kooha Kwon: kwonkh0424@gmail.com


