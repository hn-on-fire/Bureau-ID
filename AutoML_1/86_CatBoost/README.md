# Summary of 86_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
- **depth**: 9
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

2.6 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.328652 | nan           |
| auc       | 0.903386 | nan           |
| f1        | 0.786416 |   0.453747    |
| accuracy  | 0.828358 |   0.601084    |
| precision | 0.846154 |   0.695655    |
| recall    | 1        |   0.000871101 |
| mcc       | 0.686974 |   0.453747    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.328652 |  nan        |
| auc       | 0.903386 |  nan        |
| f1        | 0.770459 |    0.601084 |
| accuracy  | 0.828358 |    0.601084 |
| precision | 0.690519 |    0.601084 |
| recall    | 0.871332 |    0.601084 |
| mcc       | 0.647285 |    0.601084 |


## Confusion matrix (at threshold=0.601084)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     724 |                     173 |
| Labeled as DECLINED |                      57 |                     386 |

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
