# Summary of 34_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
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

1.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.322281 |  nan        |
| auc       | 0.900418 |  nan        |
| f1        | 0.789991 |    0.486408 |
| accuracy  | 0.826866 |    0.595438 |
| precision | 0.8      |    0.709714 |
| recall    | 1        |    0        |
| mcc       | 0.693319 |    0.486408 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.322281 |  nan        |
| auc       | 0.900418 |  nan        |
| f1        | 0.771203 |    0.595438 |
| accuracy  | 0.826866 |    0.595438 |
| precision | 0.684764 |    0.595438 |
| recall    | 0.882619 |    0.595438 |
| mcc       | 0.648738 |    0.595438 |


## Confusion matrix (at threshold=0.595438)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     717 |                     180 |
| Labeled as DECLINED |                      52 |                     391 |

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
