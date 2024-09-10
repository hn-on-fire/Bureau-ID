# Summary of 77_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.1
- **max_depth**: 4
- **min_child_weight**: 5
- **subsample**: 0.7
- **colsample_bytree**: 0.6
- **eval_metric**: auc
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

2.1 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.323192 | nan           |
| auc       | 0.900789 | nan           |
| f1        | 0.784629 |   0.44504     |
| accuracy  | 0.835075 |   0.583109    |
| precision | 0.865385 |   0.75234     |
| recall    | 1        |   0.000796279 |
| mcc       | 0.683801 |   0.44504     |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.323192 |  nan        |
| auc       | 0.900789 |  nan        |
| f1        | 0.776542 |    0.583109 |
| accuracy  | 0.835075 |    0.583109 |
| precision | 0.703297 |    0.583109 |
| recall    | 0.866817 |    0.583109 |
| mcc       | 0.656979 |    0.583109 |


## Confusion matrix (at threshold=0.583109)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     735 |                     162 |
| Labeled as DECLINED |                      59 |                     384 |

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
