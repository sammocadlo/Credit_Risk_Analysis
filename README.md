# Credit_Risk_Analysis

## Overview of Analysis

Credit risk is inherently an unbalanced classification problem, as good loans will outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. The libraries and algorithms that were used to build and evaluate these models are below:

    imbalanced-learn
    scikit-learn
    RandomOverSampler
    SMOTE algorithms
    ClusterCentroids algorithm
    SMOTEENN algorithm
    BalancedRandomForestClassifier (bias reduction model)
    EasyEnsembleClassifier (bias reduction model)


## Results

Results from Oversampling -
![image](https://user-images.githubusercontent.com/105682444/197395999-9c0027b7-f8b9-47ea-a366-9860f4502c8c.png)

SMOTE Oversampling
![image](https://user-images.githubusercontent.com/105682444/197396022-eb636085-141a-4c2c-a4b7-f94901a8accd.png)

Undersampling
![image](https://user-images.githubusercontent.com/105682444/197396041-e84b18bb-a69d-4689-82bb-50f4c4daf88e.png)

Combination - Over and Undersampling
![image](https://user-images.githubusercontent.com/105682444/197396066-97aa0600-aab8-4eae-88dd-149098ac48d6.png)

## Summary

When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.
