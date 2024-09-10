# Summary of 132_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 20
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

3.0 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.382676 |  nan        |
| auc       | 0.875322 |  nan        |
| f1        | 0.784629 |    0.535318 |
| accuracy  | 0.821642 |    0.547167 |
| precision | 0.75     |    0.604206 |
| recall    | 1        |    0        |
| mcc       | 0.683801 |    0.535318 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.382676 |  nan        |
| auc       | 0.875322 |  nan        |
| f1        | 0.781336 |    0.547167 |
| accuracy  | 0.821642 |    0.547167 |
| precision | 0.656923 |    0.547167 |
| recall    | 0.963883 |    0.547167 |
| mcc       | 0.673272 |    0.547167 |


## Confusion matrix (at threshold=0.547167)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     674 |                     223 |
| Labeled as DECLINED |                      16 |                     427 |

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
