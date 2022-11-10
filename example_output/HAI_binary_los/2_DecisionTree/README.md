# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 3
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

35.0 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.210423 |  nan        |
| auc       | 0.887944 |  nan        |
| f1        | 0.952547 |    0.680592 |
| accuracy  | 0.912102 |    0.680592 |
| precision | 1        |    0.941225 |
| recall    | 1        |    0.286134 |
| mcc       | 0.421553 |    0.872935 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.210423 |  nan        |
| auc       | 0.887944 |  nan        |
| f1        | 0.952547 |    0.680592 |
| accuracy  | 0.912102 |    0.680592 |
| precision | 0.924769 |    0.680592 |
| recall    | 0.982045 |    0.680592 |
| mcc       | 0.398168 |    0.680592 |


## Confusion matrix (at threshold=0.680592)
|                                |   Predicted as High-infection-rate |   Predicted as Low-infection-rate |
|:-------------------------------|-----------------------------------:|----------------------------------:|
| Labeled as High-infection-rate |                               1249 |                              2999 |
| Labeled as Low-infection-rate  |                                674 |                             36865 |

## Learning curves
![Learning curves](learning_curves.png)

## Decision Tree 

### Tree #1
![Tree 1](learner_fold_0_tree.svg)

### Rules

if (Compared to National > 1.5) and (Compared to National <= 2.5) then class: Low-infection-rate (proba: 100.0%) | based on 68,226 samples

if (Compared to National <= 1.5) and (Measure Name > 3.5) and (Measure Name > 21.5) then class: Low-infection-rate (proba: 88.25%) | based on 25,266 samples

if (Compared to National <= 1.5) and (Measure Name > 3.5) and (Measure Name <= 21.5) then class: Low-infection-rate (proba: 74.59%) | based on 22,461 samples

if (Compared to National <= 1.5) and (Measure Name <= 3.5) and (Measure ID > 43.0) then class: High-infection-rate (proba: 63.88%) | based on 4,895 samples

if (Compared to National > 1.5) and (Compared to National > 2.5) and (Measure ID <= 43.5) then class: Low-infection-rate (proba: 79.31%) | based on 2,194 samples

if (Compared to National <= 1.5) and (Measure Name <= 3.5) and (Measure ID <= 43.0) then class: Low-infection-rate (proba: 100.0%) | based on 1,605 samples

if (Compared to National > 1.5) and (Compared to National > 2.5) and (Measure ID > 43.5) then class: High-infection-rate (proba: 68.21%) | based on 714 samples





## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions for class 0 (Fold 1)
![SHAP worst decisions class 0 from Fold 1](learner_fold_0_shap_class_0_worst_decisions.png)
### Top-10 Best decisions for class 0 (Fold 1)
![SHAP best decisions class 0 from Fold 1](learner_fold_0_shap_class_0_best_decisions.png)
### Top-10 Worst decisions for class 1 (Fold 1)
![SHAP worst decisions class 1 from Fold 1](learner_fold_0_shap_class_1_worst_decisions.png)
### Top-10 Best decisions for class 1 (Fold 1)
![SHAP best decisions class 1 from Fold 1](learner_fold_0_shap_class_1_best_decisions.png)

[<< Go back](../README.md)
