# Brain-Tumor
Prediction of Brain Tumor Using Machine Learning Model

**BRAIN TUMOR**

A cancerous or non-cancerous mass or growth of abnormal cells in the brain.

**Symptoms:**
* New or increasingly strong headaches
* Blurred vision
* Loss of balance
* Confusion
*seizures

**Treatment:**
Brain tumors are treated with surgery, radiation therapy and chemotherapy.

**BRAIN TUMOR CLASSIFICATION:**

Medulloblastoma - A cancerous brain tumor that starts in the lower back part of the brain
Glioma - A type of tumor that occurs in the brain and spinal cord.
RhabdoidTu - A type of cancer that usually forms in the kidney or central nervous system (the brain and spinal cord) but can also form in soft tissues in other areas of the body.
Normal - The Particular individual does not have a brain tumor.
PNET - Primitive Neuro-Ectodermal Tumor(PNET) is a type of cancerous tumor that appear similar under the microscope to medulloblastoma but occur primarily in the top part of the brain (the cerebrum).

**FEATURE SELECTION USING ANOVA TEST**

Feature selection methods are intended to reduce the number of input variables to those that are believed to be most useful to a model in order to predict the target variable.

**ANOVA:**

ANOVA is an acronym for “analysis of variance” and is a parametric statistical hypothesis test for determining whether the means from two or more samples of data (often three or more) come from the same distribution or not.
The results of this test can be used for feature selection where those features that are independent of the target variable can be removed from the dataset.

**MODEL TRAINING:**

**LOGISTIC REGRESSION**

Logistic regression is used for solving classification problems.
It is used for predicting the categorical dependent variable using a given set of independent variables.
Logistic regression predicts the output of a categorical dependent variable. Therefore the outcome must be a categorical or discrete value. It can be either Yes or No, 0 or 1, true or False, etc.

**K-NEAREST NEIGHBOR**

K-NN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories.
The k-NN algorithm stores all the available data and classifies a new data point based on the similarity. This means when new data appears then it can be easily classified into a good suite category by using K- NN algorithm.
It is also called a lazy learner algorithm because it does not learn from the training set immediately instead it stores the dataset and at the time of classification, it performs an action on the dataset.

**RANDOM FOREST CLASSIFIER**
Random Forest is a classifier that contains a number of decision trees on various subsets of the given dataset and takes the average to improve the predictive accuracy of that dataset.
The greater number of trees in the forest leads to higher accuracy and prevents the problem of overfitting.

**DECISION TREE CLASSIFIER**
It is a graphical representation for getting all the possible solutions to a problem/decision based on given conditions.
It is a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome.

**SUPPORT VECTOR CLASSIFIER**
The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that can easily put the new data point in the correct category in the future. This best decision boundary is called a hyperplane.
SVM chooses the extreme points/vectors that help in creating the hyperplane.
These extreme cases are called support vectors, and hence algorithm is termed a Support Vector Machine.

**XGBOOST CLASSIFIER**
XGBoost, which stands for Extreme Gradient Boosting, is a scalable, distributed gradient-boosted decision tree (GBDT) machine learning library.

It uses sequentially-built shallow decision trees to provide accurate results and a highly-scalable training method that avoids overfitting.

ACCURACY OF MACHINE LEARNING MODELS

![image](https://github.com/Dhivyadd20/Brain-Tumor/assets/129213031/472e5dd7-ea88-4210-845b-9b5a6ced781f)
