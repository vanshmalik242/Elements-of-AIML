CLASSIFICATION TASK
Classification in machine learning is a type of supervised learning approach where the goal is to predict the category or class of an instance that are based on its features. In classification it involves training model ona dataset that have instances or observations that are already labeled with Classes and then using that model to classify new, and unseen instances into one of the predefined categories.

MACHINE LEARNING CLASSIFICATION ALGORITHMS
dataset used :- cpu.arff
STEPS INVOLVED
NORMALISE THE DATASET
![image](https://github.com/user-attachments/assets/5545c0a6-456a-4d43-abba-cee6ffc99a2b)
CLASSIFIERS USED
DecisionStump

A decision stump is a machine learning model consisting of a one-level decision tree.That is, it is a decision tree with one internal node (the root) which is immediately connected to the terminal nodes (its leaves).

CROSS VALIDATION
10 FOLDS
![image](https://github.com/user-attachments/assets/4e991e06-9847-4414-a288-bf844849ffa0)
5 FOLDS
![image](https://github.com/user-attachments/assets/db8b0ec3-d604-48b8-8e1b-a55ba7deaddc)
PERCENTAGE SPLIT
80%
![image](https://github.com/user-attachments/assets/10bc260e-527f-4f5d-a0cb-55ef5a90aaf7)
RandomForest

Random Forest uses numerous decision trees to increase prediction accuracy and reduce overfitting. It constructs many trees and integrates their predictions to create a reliable model. Diversity is added by using a random dataset and characteristics in each tree.

CROSS VALIDATION
10 FOLDS
![image](https://github.com/user-attachments/assets/dbe35b80-9c0e-4b54-9144-bac1b5659c7b)
5 FOLDS
![image](https://github.com/user-attachments/assets/fbab0de1-72ce-4177-99d6-20fdc08ce334)
PERCENTAGE SPLIT
80%
![image](https://github.com/user-attachments/assets/a5020b94-6261-4126-a348-19e27704f73c)
NaiveBayes

Naive Bayes which describes the probability of an event, based on prior knowledge of conditions that might be related to the event. Naive Bayes classifiers assume that the presence (or absence) of a particular feature of a class is unrelated to the presence (or absence) of any other feature, given the class variable

CROSS VALIDATION
10 FOLDS
![image](https://github.com/user-attachments/assets/5dde12cb-1baa-431a-9653-a77ac59abe3e)
5 FOLDS
![image](https://github.com/user-attachments/assets/723658bc-a347-4114-a6ad-3c58a146d60e)
PERCENTAGE SPLIT
80%
![image](https://github.com/user-attachments/assets/21024e87-f390-41c3-bcb0-670db72ece6e)
Logistic Regression Classification

In Logistic regression is classification algorithm used to estimate discrete values, typically binary, such as 0 and 1, yes or no. It predicts the probability of an instance belonging to a class that makes it essectial for binary classification problems like spam detection or diagnosing disease.

CROSS VALIDATION
10 FOLDS
![image](https://github.com/user-attachments/assets/7eb1c49c-44e4-40f8-b907-be060301bdff)
5 FOLDS
![image](https://github.com/user-attachments/assets/66094c66-1c9c-46a3-bf94-89d39cee2784)
PERCENTAGE SPLIT
80%
![image](https://github.com/user-attachments/assets/ec4935f5-b3a0-4cc9-b240-5c91a9fb3542)
GLOSSARY
TP Rate: The proportion of correctly classified positive instances out of all actual positive instances.

FP Rate: The proportion of incorrectly classified negative instances out of all actual negative instances.

Precision: The proportion of correctly classified positive instances out of all instances classified as positive.

Recall: The proportion of correctly classified positive instances out of all actual positive instances (also known as True Positive Rate).

F-measure: The harmonic mean of precision and recall, providing a balance between the two metrics.

MCC (Matthews Correlation Coefficient): A measure of the quality of binary classifications, considering true and false positives and negatives.

ROC Area: The area under the Receiver Operating Characteristic curve, representing the model's ability to distinguish between positive and negative classes.

PRC Area: The area under the Precision-Recall curve, highlighting the trade-off between precision and recall for different thresholds.













