# Summary of 122_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.8
- **min_samples_split**: 50
- **max_depth**: 6
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

2.9 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.325417 |  nan        |
| auc       | 0.896003 |  nan        |
| f1        | 0.788204 |    0.485708 |
| accuracy  | 0.825373 |    0.615238 |
| precision | 0.764103 |    0.670809 |
| recall    | 1        |    0        |
| mcc       | 0.690147 |    0.485708 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.325417 |  nan        |
| auc       | 0.896003 |  nan        |
| f1        | 0.774131 |    0.615238 |
| accuracy  | 0.825373 |    0.615238 |
| precision | 0.676223 |    0.615238 |
| recall    | 0.905192 |    0.615238 |
| mcc       | 0.654605 |    0.615238 |


## Confusion matrix (at threshold=0.615238)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     705 |                     192 |
| Labeled as DECLINED |                      42 |                     401 |

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
