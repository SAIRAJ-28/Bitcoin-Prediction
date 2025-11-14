Machine Learning Algorithms

*KNN Algorithm*


KNN is one of the most basic yet essential classification algorithms in machine learning.
It belongs to the supervised learning domain and finds intense application in pattern recognition, data mining, and intrusion detection.  
Steps:
1)Split the dataset into training (80%) and testing (20%) sets.
2)Choose an appropriate value for K (the number of neighbors).
3)Compute distances between data points using Euclidean distance.
4)Classify the test set based on majority voting from the K nearest neighbors.
Hyperparameter Tuning for KNN:n_neighbors: The number of nearest neighbors used for prediction. You can tune this parameter using Grid Search or Random Search to find the optimal value.
Advantages:
•	It's easy to understand and simple to implement.
•	It can be used for both classification and regression problems.
•	It's ideal for non-linear data since there's no assumption about underlying data.
•	It can naturally handle multi-class cases.
Disadvantages:
•	computational expense
•	slow speed, memory and storage issues for large datasets, 
•	sensitivity to the choice of k and the distance metric, 
•	susceptibility to the curse of dimensionality.


*Gradient Boosting Algorithm*


Gradient Boosting is an ensemble technique that builds multiple weak learners (decision trees) sequentially to improve prediction accuracy.
Implementation Steps:
1)Split the dataset into training and testing sets (same as KNN).
2)Initialize a model with a learning rate and number of estimators.
3)Sequentially fit decision trees to correct errors from previous models.
4)Combine outputs from all trees for final predictions
Hyperparameter Tuning:Conducted grid search to optimize parameters such as learning rate, max depth, and number of estimators, resulting in improved performance..
Advantages:
•	handle complex relationships in data 
•	protect against overfitting
Disadvantages:
•	Sensitive to outliers



*Comparison and Justification*

Between KNN and Gradient Boosting, Gradient Boosting demonstrated superior performance across all metrics, owing to its ability to handle non-linear relationships and provide optimal separation between classes. 
While Naive Bayes is computationally efficient, it is sensitive to the independence assumption, which may not hold for this dataset. 
