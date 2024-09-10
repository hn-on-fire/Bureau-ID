# Summary of 29_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.025
- **depth**: 6
- **rsm**: 0.9
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

2.8 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.325047 | nan          |
| auc       | 0.900621 | nan          |
| f1        | 0.789128 |   0.569627   |
| accuracy  | 0.83209  |   0.569627   |
| precision | 0.826923 |   0.709265   |
| recall    | 1        |   0.00024974 |
| mcc       | 0.686974 |   0.384337   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.325047 |  nan        |
| auc       | 0.900621 |  nan        |
| f1        | 0.789128 |    0.569627 |
| accuracy  | 0.83209  |    0.569627 |
| precision | 0.674679 |    0.569627 |
| recall    | 0.950339 |    0.569627 |
| mcc       | 0.682818 |    0.569627 |


## Confusion matrix (at threshold=0.569627)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     694 |                     203 |
| Labeled as DECLINED |                      22 |                     421 |

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
