# Summary of 74_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.8
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

2.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.322248 |  nan        |
| auc       | 0.900078 |  nan        |
| f1        | 0.788204 |    0.467009 |
| accuracy  | 0.828358 |    0.591181 |
| precision | 0.78022  |    0.702821 |
| recall    | 1        |    0        |
| mcc       | 0.690147 |    0.467009 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.322248 |  nan        |
| auc       | 0.900078 |  nan        |
| f1        | 0.776265 |    0.591181 |
| accuracy  | 0.828358 |    0.591181 |
| precision | 0.682051 |    0.591181 |
| recall    | 0.900677 |    0.591181 |
| mcc       | 0.657628 |    0.591181 |


## Confusion matrix (at threshold=0.591181)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     711 |                     186 |
| Labeled as DECLINED |                      44 |                     399 |

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
