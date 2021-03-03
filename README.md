# Rating Predictions of Stack Overflow Questions

## Variable Descriptions
<p> Id: Unique number of each questions
Title: The title of questions
Body: The questions
CreationDate: Which time question created
Y: Quality class
HQ: High-quality posts with a total of 30+ score and without a single edit. (2)
LQ_EDIT: Low-quality posts with a negative score, and multiple community edits. However, they still remain open after those changes. (1)
LQ_CLOSE: Low-quality posts that were closed by the community without a single edit. (0) 
</p>

## Machine Learning Models Used:
 * Logistic Regression
 * Random Forest
 * KNN
 * Decision Tree Classifier

## Accuracy : 80% Random Forest Classifier

## Concepts used:
* Natural Language Processing
* Bag-of-words
* Stopwords
* Count Vectorizer

