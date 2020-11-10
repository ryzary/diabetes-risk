# Diabetes Risk Prediction

## Introduction
Approximately 50% of people with diabetes are undiagnosed due to its long period of asymptomatic phase (Islam et al.,2020). Early detection of diabetes is therefore crucial.
<br>
<br>
This project aims to predict the likelihood of having diabetes using the data of newly diabetic and potentially diabetic patients from Sylhet Diabetes Hospital in Bangladesh.

## Dataset
http://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset.#
<br>
Attributes:
Age, Gender, Polyuria, Polydipsia, Polyphagia, Irritability, Delayed healing, Genital thrush,Partial paresis, Alopecia, Class.
(Definitions are provided in EDA_feature_selection.ipynb)

## EDA
### Attributes with Respect to "positive-negative" Diabetes Status
![alt text](https://github.com/ryzary/diabetes-risk/blob/main/img/symptoms_occurence_pn.png)

### Number of Cases on Different Age Groups
![alt text](https://github.com/ryzary/diabetes-risk/blob/main/img/class_age_group.png)


## Model Accuracy
- Logistic Regression: 0.92
- Random Forest Classifier: 0.979 (10-fold mean cross-validation score)



## Reference
Islam M.M.F., Ferdousi R., Rahman S., Bushra H.Y. (2020) Likelihood Prediction of Diabetes at Early Stage Using Data Mining Techniques. In: Gupta M., Konar D., Bhattacharyya S., Biswas S. (eds) Computer Vision and Machine Intelligence in Medical Image Analysis. Advances in Intelligent Systems and Computing, vol 992. Springer, Singapore. https://doi.org/10.1007/978-981-13-8798-2_12


