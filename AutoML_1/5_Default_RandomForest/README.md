# Summary of 5_Default_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 30
- **max_depth**: 4
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

3.5 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.328412 |  nan        |
| auc       | 0.8928   |  nan        |
| f1        | 0.788204 |    0.592623 |
| accuracy  | 0.828358 |    0.637479 |
| precision | 0.747253 |    0.664964 |
| recall    | 1        |    0        |
| mcc       | 0.690147 |    0.592623 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.328412 |  nan        |
| auc       | 0.8928   |  nan        |
| f1        | 0.775828 |    0.637479 |
| accuracy  | 0.828358 |    0.637479 |
| precision | 0.682676 |    0.637479 |
| recall    | 0.89842  |    0.637479 |
| mcc       | 0.6568   |    0.637479 |


## Confusion matrix (at threshold=0.637479)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     712 |                     185 |
| Labeled as DECLINED |                      45 |                     398 |

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
