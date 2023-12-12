# credit-risk-classification

Overview:
The purpose of this analysis is to leverage machine learning models in predicting credit risk for loan applicants. The models will generate reports on accuracy, precision and recall helping the company make informed descisions on whether to adopt the model for credit risk assessment.


Model Performance Metrics

Class 0 (Negative Class - e.g., Non-default):
Precision: 99%
Recall: 100%
F1-score: 100%
Support: 18,653

Class 1 (Positive Class - e.g., Default):
Precision: 99%
Recall: 84%
F1-score: 91%
Support: 731

Overall Metrics:
Accuracy: 99%
Macro Average F1-score: 95%
Weighted Average F1-score: 99%

The model performance well in the negative case where false positives and negatives were kept to a minimum at near 100%

The positive case was correct 99% of the time. However, the model recall was 84% which meant that the model missed some instances of actual defaults.

Overall, accuracy and F1 scores suggest that his model is highly reliable.

Recommendation:
Even though the model proved to be reliable, it up to business to decide if deployment of this model is within the company's risk tolerance.
