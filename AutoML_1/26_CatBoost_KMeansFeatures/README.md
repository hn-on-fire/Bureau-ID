# Summary of 26_CatBoost_KMeansFeatures

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.2
- **depth**: 6
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

2.5 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.323268 | nan           |
| auc       | 0.899726 | nan           |
| f1        | 0.790485 |   0.46541     |
| accuracy  | 0.829104 |   0.46541     |
| precision | 0.846154 |   0.775854    |
| recall    | 1        |   6.07137e-05 |
| mcc       | 0.689143 |   0.46541     |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.323268 |   nan       |
| auc       | 0.899726 |   nan       |
| f1        | 0.790485 |     0.46541 |
| accuracy  | 0.829104 |     0.46541 |
| precision | 0.664615 |     0.46541 |
| recall    | 0.975169 |     0.46541 |
| mcc       | 0.689143 |     0.46541 |


## Confusion matrix (at threshold=0.46541)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     679 |                     218 |
| Labeled as DECLINED |                      11 |                     432 |

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
