# Supervised-Machine-Learning-Classifier
- Healthcare: Wearables/Sensors

- Predicting quality of personal exercise activity as part of the quantified self movement.

- Machine learning classification model was created to predict how well members of the quantified self movement perform weight lifting exercises as part of their personal activity.


Processing Instructions:
- HTML and pdf file are included.
- https://kimkirk.github.io/Supervised-Machine-Learning-Classifier/ to view HTML version of report
- To improve reproducibility of the data analysis, an R-Markdown file is included. 
- Use R Studio or other application to read R-Markdown file.

Steps to Transformation and Results:
- Human Activity Recoginition data were downloaded from "http://groupware.les.inf.puc-rio.br/har" and loaded into R as csv file.
- The outcome (CLASSE) and predictor variables were identified and analyzed for missing values, irregular values, outliers, correlation between predictors, class imbalance, non-normal distributions, etc.
- Data were preprocessed by removal of missing values and irregular values (which were found to be intentional), removel of correlated predictors, scaled and centered, binned to correct class imbalance, etc.
- Feature engineering was conducted to select and transform relevant variables.
- The classification model was created using Random Forest algorithm.
- The classifier had an out-of-sample accuracy rate of 99.82%.
