# Liver_cirhossis
“Constructing a Machine Learning Model to Determine the Patient Survival Rate in Cirrhosis of Liver” 



# Cirrhosis of Liver – Predicting Patient Survival with Machine Learning

## Project Overview

This project aims to build a machine learning model to predict the survival rates of patients diagnosed with cirrhosis of the liver. Cirrhosis is a progressive, irreversible disease with limited treatment options apart from liver transplantation. By leveraging historical clinical data from the Mayo Clinic, this study provides predictive insights to aid clinical decision-making, resource allocation, and patient care planning.

## Motivation

* Improve prognosis: Deliver insights into survival rates to optimize patient care.
* Resource planning: Enable hospitals to prepare for high-risk cases.
* Clinical decision support: Assist clinicians in determining treatment urgency, including liver transplant eligibility.

##  Objectives

* Develop a predictive model using clinical and demographic data.
* Identify key features associated with survival outcomes.
* Evaluate the model's performance using standard ML metrics.
* Offer actionable insights for medical professionals.

## Dataset

* Source: Kaggle ([Cirrhosis Patient Survival Prediction Dataset](https://www.kaggle.com/datasets/joebeachcapital/cirrhosis-patient-survival-prediction))
* Records: 418 patients
* Features: 20 variables including age, sex, ascites, bilirubin, albumin, prothrombin time, etc.
* Target Variable: Survival status (Death, Censored, Censored due to liver injury)

## Methods

### Week-by-Week Breakdown

* Week 1: Data exploration and visualization
* Week 2: Data cleaning, label encoding, normalization
* Week 3: Feature engineering, status encoding, data visualization
* Weeks 5–6: Model training (Naive Bayes, SVM, Decision Tree)
* Week 7: Model validation using K-Fold cross-validation
* Week 8: Final evaluation and documentation

### Model Evaluation Metrics

| Model                       | Accuracy  | Precision | Recall | F1 Score |
| --------------------------- | --------- | --------- | ------ | -------- |
| Naive Bayes                 | 65.1%     | 0.562     | 0.552  | 0.552    |
| SVM                         | 68.3%     | 0.457     | 0.521  | 0.486    |
| Decision Tree               | 55.6%     | 0.459     | 0.452  | 0.452    |
| **Cross-Validation (Mean)** | **69.2%** |           |        |          |

## Key Features Influencing Survival

* Number of days observed
* Age
* Bilirubin levels
* Albumin levels
* Platelet count
* Prothrombin time

##  Limitations

* Dataset imbalance and missing data
* Model generalizability to diverse populations
* Limited interpretability of complex models
* Ethical concerns around clinical use and privacy

## Conclusion

While Naive Bayes provided the most balanced results among the tested models, continued refinement with more advanced algorithms and domain expert collaboration is recommended. The project highlights the potential of data-driven tools in improving liver disease management and patient outcomes.

## References

* [Cirrhosis Prediction Dataset – Kaggle](https://www.kaggle.com/datasets/joebeachcapital/cirrhosis-patient-survival-prediction)
* [Nature Reviews Gastroenterology & Hepatology](https://doi.org/10.1038/s41575-023-00759-2)
* [NCBI – Hepatic Cirrhosis](https://www.ncbi.nlm.nih.gov/books/NBK482419/)
*  [Predicting Cirrhosis Outcomes – Kaggle Notebook](https://www.kaggle.com/code/jocelyndumlao/predicting-cirrhosis-outcomes)

