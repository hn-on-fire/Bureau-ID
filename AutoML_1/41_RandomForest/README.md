# Summary of 41_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.7
- **min_samples_split**: 40
- **max_depth**: 3
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

2.2 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.337897 |  nan        |
| auc       | 0.881726 |  nan        |
| f1        | 0.788909 |    0.498759 |
| accuracy  | 0.823881 |    0.498759 |
| precision | 1        |    0.641974 |
| recall    | 1        |    0        |
| mcc       | 0.691187 |    0.498759 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.337897 |  nan        |
| auc       | 0.881726 |  nan        |
| f1        | 0.788909 |    0.498759 |
| accuracy  | 0.823881 |    0.498759 |
| precision | 0.653333 |    0.498759 |
| recall    | 0.995485 |    0.498759 |
| mcc       | 0.691187 |    0.498759 |


## Confusion matrix (at threshold=0.498759)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     663 |                     234 |
| Labeled as DECLINED |                       2 |                     441 |

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
