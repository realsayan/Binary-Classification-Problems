# Binary-Classification-Problems
Projects dealing with binary classification problems

- **Predict Recurrence of events from Breast Cancer Dataset** - </br>
EDA to understand the data, clean the data and perform missing value imputation. </br>
Convert textual data to appropriate numerical form. </br>
Build models- linear models like Logistic Regression as well as tree based models like Random Forrest. </br>
Based on the evaluation metrics perform hyperparameter tuning (using Cross Validation techniques to identify best values). </br>
When comparing the models, consider precision and recall as more important than accuracy. </br>
The models built did not give great result for recall. </br>
It could be partly because the data available for training was pretty small. </br>
Hence there is scope for improvement and trying out more complex algorithms to build models in future. <br>

- **Gender Recognition using features of the Voice sample Dataset** - </br>
EDA to understand the data - the data does not contain any missing values. </br>
Study the correlation between different independent variables and remove very highly correlated ones. </br>
After the train and test split of data, standard scaling is done on both the datasets separately. </br>
Build models- Logistic Regression, Gaussian Naïve Bayes, Random Forest, K Neighbors and SVM. </br>
For all the algorithms a basic model is built followed by a hyperparameter tuned one. </br>
Fairly good result is obtained for all metrics like accuracy score, precision, recall and F1. </br>
Considering the F1 scores as well as robustness (bias-variance trade-off) of the models, both KNN and SVM did very well. </br>
