# Summary of 3_Default_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
- **depth**: 6
- **rsm**: 1
- **loss_function**: Logloss
- **eval_metric**: AUC
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

1.3 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.324859 | nan           |
| auc       | 0.899233 | nan           |
| f1        | 0.785579 |   0.57565     |
| accuracy  | 0.831343 |   0.57565     |
| precision | 0.807692 |   0.710717    |
| recall    | 1        |   0.000119401 |
| mcc       | 0.683801 |   0.417287    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.324859 |   nan       |
| auc       | 0.899233 |   nan       |
| f1        | 0.785579 |     0.57565 |
| accuracy  | 0.831343 |     0.57565 |
| precision | 0.677578 |     0.57565 |
| recall    | 0.934537 |     0.57565 |
| mcc       | 0.675257 |     0.57565 |


## Confusion matrix (at threshold=0.57565)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     700 |                     197 |
| Labeled as DECLINED |                      29 |                     414 |

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
