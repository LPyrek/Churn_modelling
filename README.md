The project aimed to analyze the phenomenon of customer churn in the banking sector. The “The bank customer churn dataset” was used. The main task was to examine the factors influencing a customer’s decision to leave and to create machine learning models to predict this phenomenon.


Three classification models were built: KNN, SVM (with an RBF kernel), and Random Forest.
Random Forest achieved the best results in cross-validation (CV), obtaining the highest values for Accuracy, Recall, and Specificity.
On the test set, there was a decrease in performance for all models, particularly in the Recall metric, indicating difficulties in identifying positive cases (customer churn).
Despite the highest Accuracy in CV, Random Forest had the lowest Recall on the test set.
SVM proved to be the best compromise between Accuracy and Recall on the test set and was chosen as the final model (accuracy = 0.835).
By conducting EDA and analyzing model interpretability plots, it was found that the most important variables influencing customer churn were Age and NumOfProducts.
The model can still be improved by, for example, changing threshold values, transforming and creating new variables (Feature Engineering), or using other models like CatBoost or GradientBoosting.
