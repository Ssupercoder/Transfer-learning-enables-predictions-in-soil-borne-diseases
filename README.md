# readme
Inhibiting the occurrence of soil-borne diseases is considered as the most favorable approach for promoting sustainable agricultural development. Constructing soil disease 
prediction models can serve precision agriculture. However, the analysis results of the metaframework often contradict each other, causing inconsistency in the important 
features of machine learning results. Therefore, it is necessary to compare the classification accuracy of various machine learning models and further optimize the features of 
the models to enhance their classification accuracy. Here, we conducted a comparison of eight common machine learning algorithms (XGBoost, CatBoost, Decision Tree, LGBM, Naïve 
Byes, Perceptron, Logistic, and Random Forest) at the levels of family, genus, and class. The important features of the model were extracted based on the differences in model 
accuracy and important features, followed by an interpretable analysis of these important features using feature importance. Subsequently, the data underwent resampling using 
the SMOTE algorithm, and the results show that the SMOTE-Transformer model performs well, surpassing the training results of the voting and stacking strategies, with an 
accuracy reaching 90%. We have also deployed the SMOTE-Transformer model on sequencing data, which has an accuracy of over 80%. The construction of SMOTE-Transformer model 
provides a new idea for soil microbial data analysis by greatly improving the accuracy and robustness of soil microbial data processing tools.
