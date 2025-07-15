This folder contains the code to extract important features selected by the models. The code uses the models stored in **machine learning/models** to allot importance scores to each feature in the model. The extracted features are stored as CSV files in the folder.

- **classifiers_features_permutation_imp**: The features from the classifier models using permutation importance scores
- **regressors_features_permutation_imp**: The features from the regression models using permutation importance scores
- **classifiers_features_SHAP**: The features from the classifier models using SHAP importance scores
- **regressors_features_SHAP**: The features from the regression models using SHAP importance scores