# Train Delay Prediction Project 
## 📌 Overview <br>
This project aims to build a machine learning model that predicts train delays based on real world data. The prediction is made on the basis of several coulmns present in the csv file. The csv file contains 21 columns including TRAIN_NUMBER, ID_TRAIN_DEF, TRAIN_TYPE, TRAIN_SUB_TYPE .... ALWNC, DISTANCE, NEXT_DELAY. 

Multiple machine learning models were used including:
- **Random Forest Regressor**
- **XGBoost Regressor**
- **LightGBM Regressor**

To enhance prediction accuracy, we implemented a stacked ensemble model that combines predictions from RandomForest, XGBoost and LightGBM, using an **MLPRegressor** as the meta-model. This stacking approach enables the model to generalize better by leveraging the strengths of multiple learners. Few visual aids like graphs and confusion matrix have also been created to show the results.
