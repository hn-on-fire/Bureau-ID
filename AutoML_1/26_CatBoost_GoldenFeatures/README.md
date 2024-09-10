# Summary of 26_CatBoost_GoldenFeatures

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

2.4 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.318288 | nan           |
| auc       | 0.901705 | nan           |
| f1        | 0.788427 |   0.43393     |
| accuracy  | 0.826119 |   0.5653      |
| precision | 0.826923 |   0.787039    |
| recall    | 1        |   3.12969e-05 |
| mcc       | 0.687928 |   0.43393     |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.318288 |    nan      |
| auc       | 0.901705 |    nan      |
| f1        | 0.764408 |      0.5653 |
| accuracy  | 0.826119 |      0.5653 |
| precision | 0.692308 |      0.5653 |
| recall    | 0.853273 |      0.5653 |
| mcc       | 0.637609 |      0.5653 |


## Confusion matrix (at threshold=0.5653)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     729 |                     168 |
| Labeled as DECLINED |                      65 |                     378 |

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
