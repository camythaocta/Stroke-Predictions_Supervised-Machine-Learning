# Stroke-Predictions_Imbalanced-Data
In this project, the dataset used is about people who have had a stroke and not, which is considered from several causes or features. This dataset is also an imbalanced dataset where the target class has an uneven distribution of observations. Then, several machine learning models are used to determine what factors influence stroke and what metrics are best used to predict stroke.

Conclusions:
 - All features in the dataset are used to analysing (no redundant features)
 - Individual's age affects stroke
 - bmi value is not significantly affects stroke
 - gender, marriage status, job, residence do not have much effect on having stroke, it depends on the situation and lifestyle
 - Logistic regression and Gradient Booster metrix have highest recall score (82%)
 - Using GridSearchCV is better
 - For hyperparameter tunning, random forest classifier has higher recall score (79%) and lower false negative (31) than decision tree classifier 

