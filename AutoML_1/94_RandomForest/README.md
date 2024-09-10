# Summary of 94_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 50
- **max_depth**: 7
- **eval_metric_name**: auc
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

2.6 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.322413 |  nan        |
| auc       | 0.898885 |  nan        |
| f1        | 0.790216 |    0.577013 |
| accuracy  | 0.833582 |    0.577013 |
| precision | 0.75641  |    0.690644 |
| recall    | 1        |    0        |
| mcc       | 0.690147 |    0.485421 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.322413 |  nan        |
| auc       | 0.898885 |  nan        |
| f1        | 0.790216 |    0.577013 |
| accuracy  | 0.833582 |    0.577013 |
| precision | 0.677419 |    0.577013 |
| recall    | 0.948081 |    0.577013 |
| mcc       | 0.684137 |    0.577013 |


## Confusion matrix (at threshold=0.577013)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     697 |                     200 |
| Labeled as DECLINED |                      23 |                     420 |

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
