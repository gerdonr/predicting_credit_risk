# Predicting Credit Risk

## Ensemble Learning Methods
##### This notebook take a look at two different Ensemble Algorithms, a Balanced Random Forest Classifier and an Easy Ensemble classifier, and compares them to see which one has the best performance for predicting credit risk. To assess performance we take a look at the balanced accuracy score, the confusion matrix, and the imbalanced classification report. In our example, we found that the Easy Ensemble classifer performed better than the Balanced Random Forest classifier in all three of our performance metrics. 

## Ensemble Learning Methods Conclusions
#### Which model had the best balanced accuracy score?
##### The Easy Ensemble Classifier had the best balanced accuracy score with 0.925 vs 0.787 for the Balanced Random Forest Classfier 
#### Which model had the best recall score?
##### The Easy Ensemble Classifier also had the best recall score with 0.94 vs 0.91 for the Balanced Random Forest Classifier. 
#### Which model had the best geometric mean score?
##### Once again the Easy Ensemble Classifier had the best score here with 0.93 vs 0.78 for the Balanced Random Forest Classifier.
#### What are the top three features?
##### The top 3 features were the 'total_rec_prncp','total_rec_int', and 'total_pymnt_inv' features. 

## Resampling Techniques
##### This notebook uses the same loan data as the Ensemble Learning methods notebook mentioned above and compares two different Oversampling algorithms (SMOTE and Random Oversampling), one Undersampling algorithm (CentroidClusters), and one combination (SMOTEENN) algorithm to see which one performs the best. Once again we are comparing the balanced accuracy score, confusion matrix, and imbalanced classification report between all of the models. Our results suggest that the SMOTE algorithm performed the best overall but was closely followed by the Random Oversampling algorithm. Interestingly, both of these algorithms use Oversampling as their method of balancing the data.  

## Resampling Techniques Conclusions
#### Which model had the best balanced accuracy score?
##### The SMOTE model had the best balanced accuracy score with 0.649 followed by the Random Oversampling model with 0.624, the SMOTEENN model with 0.619, and then ClusterCentroid model with 0.520. 
#### Which model had the best recall score?
##### The Random Oversampling model had the best recall score with 0.67 followed by the SMOTE model with 0.65, the SMOTEENN model with 0.55, and then ClusterCentroid model with 0.41. 
#### Which model had the best geometric mean score?
##### The SMOTE model had the highest geometric mean score with 0.65 followed by the Random Oversampling model with 0.62, the SMOTEENN model with 0.61, and lastly the ClusterCentroid model with 0.51.