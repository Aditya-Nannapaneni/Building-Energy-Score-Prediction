# Building-Energy-Score-Prediction
**TASK:**

-This is a supervised, regression machine learning task: given a set of data with targets (in this case the score) included, we want to train a model that can learn to map the features (also known as the explanatory variables) to the target.

    -Supervised problem: we are given both the features and the target
    -Regression problem: the target is a continous variable, in this case ranging from 0-100
-During training, we want the model to learn the relationship between the features and the score so we give it both the features and the answer. Then, to test how well the model has learned, we evaluate it on a testing set where it has never seen the answers!

**RESULTS:**

-	Developed a naive baseline model to compare against 5 machine learning algorithms (Linear/SVM/Random Forest/Gradient Boosting/KNN Regression), used Mean Absolute   Error (MAE) as evaluation metric.
-	Tuned Hyperparameters using Random Search & 4-fold Cross Validation to predict the Energy Star Score of a building to within 10 points. 
