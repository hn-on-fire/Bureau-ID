# Summary of 91_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.7
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

2.5 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.323379 | nan         |
| auc       | 0.89923  | nan         |
| f1        | 0.78481  |   0.559913  |
| accuracy  | 0.827612 |   0.602154  |
| precision | 0.8      |   0.714384  |
| recall    | 1        |   0         |
| mcc       | 0.685147 |   0.0566667 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.323379 |  nan        |
| auc       | 0.89923  |  nan        |
| f1        | 0.770149 |    0.602154 |
| accuracy  | 0.827612 |    0.602154 |
| precision | 0.688612 |    0.602154 |
| recall    | 0.873589 |    0.602154 |
| mcc       | 0.646824 |    0.602154 |


## Confusion matrix (at threshold=0.602154)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     722 |                     175 |
| Labeled as DECLINED |                      56 |                     387 |

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
