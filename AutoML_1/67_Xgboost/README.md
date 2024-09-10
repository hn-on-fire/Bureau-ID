# Summary of 67_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.1
- **max_depth**: 6
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

1.9 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.321896 | nan           |
| auc       | 0.901352 | nan           |
| f1        | 0.784995 |   0.472313    |
| accuracy  | 0.826866 |   0.573082    |
| precision | 0.876923 |   0.774076    |
| recall    | 1        |   0.000813992 |
| mcc       | 0.683104 |   0.107298    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.321896 |  nan        |
| auc       | 0.901352 |  nan        |
| f1        | 0.762295 |    0.573082 |
| accuracy  | 0.826866 |    0.573082 |
| precision | 0.697936 |    0.573082 |
| recall    | 0.839729 |    0.573082 |
| mcc       | 0.634601 |    0.573082 |


## Confusion matrix (at threshold=0.573082)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     736 |                     161 |
| Labeled as DECLINED |                      71 |                     372 |

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
