# Summary of 61_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.05
- **depth**: 8
- **rsm**: 1.0
- **loss_function**: Logloss
- **eval_metric**: AUC
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

2.3 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.330219 | nan          |
| auc       | 0.907321 | nan          |
| f1        | 0.786416 |   0.448054   |
| accuracy  | 0.834328 |   0.608616   |
| precision | 0.865385 |   0.663548   |
| recall    | 1        |   0.00229033 |
| mcc       | 0.686974 |   0.448054   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.330219 |  nan        |
| auc       | 0.907321 |  nan        |
| f1        | 0.772541 |    0.608616 |
| accuracy  | 0.834328 |    0.608616 |
| precision | 0.707317 |    0.608616 |
| recall    | 0.851016 |    0.608616 |
| mcc       | 0.650807 |    0.608616 |


## Confusion matrix (at threshold=0.608616)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     741 |                     156 |
| Labeled as DECLINED |                      66 |                     377 |

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
