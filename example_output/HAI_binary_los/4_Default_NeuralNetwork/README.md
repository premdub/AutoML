# Summary of 4_Default_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 16
- **learning_rate**: 0.05
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

46.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.225101 |  nan        |
| auc       | 0.871916 |  nan        |
| f1        | 0.946449 |    0.621767 |
| accuracy  | 0.898342 |    0.621767 |
| precision | 1        |    0.999993 |
| recall    | 1        |    0.621767 |
| mcc       | 0.415978 |    0.835621 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.225101 |  nan        |
| auc       | 0.871916 |  nan        |
| f1        | 0.946449 |    0.621767 |
| accuracy  | 0.898342 |    0.621767 |
| precision | 0.898342 |    0.621767 |
| recall    | 1        |    0.621767 |
| mcc       | 0        |    0.621767 |


## Confusion matrix (at threshold=0.621767)
|                                |   Predicted as High-infection-rate |   Predicted as Low-infection-rate |
|:-------------------------------|-----------------------------------:|----------------------------------:|
| Labeled as High-infection-rate |                                  0 |                              4248 |
| Labeled as Low-infection-rate  |                                  0 |                             37539 |

## Learning curves
![Learning curves](learning_curves.png)

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



[<< Go back](../README.md)
