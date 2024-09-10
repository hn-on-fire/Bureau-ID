# Summary of 92_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
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
| logloss   | 0.322798 |  nan        |
| auc       | 0.899744 |  nan        |
| f1        | 0.787476 |    0.579585 |
| accuracy  | 0.832836 |    0.579585 |
| precision | 0.764423 |    0.675923 |
| recall    | 1        |    0        |
| mcc       | 0.686974 |    0.49668  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.322798 |  nan        |
| auc       | 0.899744 |  nan        |
| f1        | 0.787476 |    0.579585 |
| accuracy  | 0.832836 |    0.579585 |
| precision | 0.679214 |    0.579585 |
| recall    | 0.936795 |    0.579585 |
| mcc       | 0.678442 |    0.579585 |


## Confusion matrix (at threshold=0.579585)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     701 |                     196 |
| Labeled as DECLINED |                      28 |                     415 |

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
