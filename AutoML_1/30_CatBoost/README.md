# Summary of 30_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
- **depth**: 5
- **rsm**: 0.8
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

2.0 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.326602 | nan           |
| auc       | 0.897189 | nan           |
| f1        | 0.786618 |   0.566793    |
| accuracy  | 0.826866 |   0.602532    |
| precision | 0.846154 |   0.689884    |
| recall    | 1        |   0.000340304 |
| mcc       | 0.686974 |   0.364061    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.326602 |  nan        |
| auc       | 0.897189 |  nan        |
| f1        | 0.774319 |    0.602532 |
| accuracy  | 0.826866 |    0.602532 |
| precision | 0.680342 |    0.602532 |
| recall    | 0.89842  |    0.602532 |
| mcc       | 0.654429 |    0.602532 |


## Confusion matrix (at threshold=0.602532)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     710 |                     187 |
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
