# Summary of 116_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.075
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

2.2 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.327068 | nan          |
| auc       | 0.898059 | nan          |
| f1        | 0.784629 |   0.476922   |
| accuracy  | 0.825373 |   0.559538   |
| precision | 0.8      |   0.715091   |
| recall    | 1        |   0.00152712 |
| mcc       | 0.683801 |   0.476922   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.327068 |  nan        |
| auc       | 0.898059 |  nan        |
| f1        | 0.783333 |    0.559538 |
| accuracy  | 0.825373 |    0.559538 |
| precision | 0.66405  |    0.559538 |
| recall    | 0.954853 |    0.559538 |
| mcc       | 0.674736 |    0.559538 |


## Confusion matrix (at threshold=0.559538)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     683 |                     214 |
| Labeled as DECLINED |                      20 |                     423 |

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
