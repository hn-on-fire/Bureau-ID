# Summary of 49_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.8
- **min_samples_split**: 40
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

2.8 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.395329 |  nan        |
| auc       | 0.875268 |  nan        |
| f1        | 0.78552  |    0.525638 |
| accuracy  | 0.823134 |    0.525638 |
| precision | 0.790698 |    0.594314 |
| recall    | 1        |    0        |
| mcc       | 0.682643 |    0.525638 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.395329 |  nan        |
| auc       | 0.875268 |  nan        |
| f1        | 0.78552  |    0.525638 |
| accuracy  | 0.823134 |    0.525638 |
| precision | 0.655589 |    0.525638 |
| recall    | 0.979684 |    0.525638 |
| mcc       | 0.682643 |    0.525638 |


## Confusion matrix (at threshold=0.525638)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     669 |                     228 |
| Labeled as DECLINED |                       9 |                     434 |

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
