# Summary of 95_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.7
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

3.1 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.325692 |  nan        |
| auc       | 0.898522 |  nan        |
| f1        | 0.788204 |    0.514476 |
| accuracy  | 0.830597 |    0.620373 |
| precision | 0.807692 |    0.685262 |
| recall    | 1        |    0        |
| mcc       | 0.690147 |    0.514476 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.325692 |  nan        |
| auc       | 0.898522 |  nan        |
| f1        | 0.78194  |    0.620373 |
| accuracy  | 0.830597 |    0.620373 |
| precision | 0.680602 |    0.620373 |
| recall    | 0.918736 |    0.620373 |
| mcc       | 0.667928 |    0.620373 |


## Confusion matrix (at threshold=0.620373)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     706 |                     191 |
| Labeled as DECLINED |                      36 |                     407 |

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
