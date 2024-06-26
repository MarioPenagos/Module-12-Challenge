## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe all machine learning models' balanced accuracy scores and the precision and recall scores.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
     * Accuracy: 99%
     * Precision: 92%
     * Recall: 95%


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Accuracy: 99%
  * Precision: 92%
  * Recall: 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? Machine learning model 2 performs better since recall is almost perfect and is higher than model 1.
* How do you know it performs best? Becuase the recall % using oversampling went up 4% almost being perfect in identifying true positives
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) yes, in this case we want to be more accurate in identifying bad loans (1) and model 2 provides a better % of recall.

If you do not recommend any of the models, please justify your reasoning.
