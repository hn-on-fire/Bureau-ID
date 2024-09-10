# Summary of 59_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 4
- **learning_rate**: 0.05
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

2.2 seconds

## Metric details
|           |    score |      threshold |
|:----------|---------:|---------------:|
| logloss   | 0.338503 | nan            |
| auc       | 0.867726 | nan            |
| f1        | 0.781193 |   0.649766     |
| accuracy  | 0.819403 |   0.649766     |
| precision | 0.651584 |   0.649766     |
| recall    | 1        |   6.34298e-144 |
| mcc       | 0.677455 |   0.466107     |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.338503 |  nan        |
| auc       | 0.867726 |  nan        |
| f1        | 0.781193 |    0.649766 |
| accuracy  | 0.819403 |    0.649766 |
| precision | 0.651584 |    0.649766 |
| recall    | 0.975169 |    0.649766 |
| mcc       | 0.675237 |    0.649766 |


## Confusion matrix (at threshold=0.649766)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     666 |                     231 |
| Labeled as DECLINED |                      11 |                     432 |

## Learning curves
![Learning curves](learning_curves.png)
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
