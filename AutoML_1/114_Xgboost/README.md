# Summary of 114_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.075
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

2.2 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.325431 | nan          |
| auc       | 0.896993 | nan          |
| f1        | 0.784629 |   0.402173   |
| accuracy  | 0.823881 |   0.524851   |
| precision | 0.865385 |   0.763715   |
| recall    | 1        |   0.00142406 |
| mcc       | 0.683801 |   0.402173   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.325431 |  nan        |
| auc       | 0.896993 |  nan        |
| f1        | 0.776091 |    0.524851 |
| accuracy  | 0.823881 |    0.524851 |
| precision | 0.669394 |    0.524851 |
| recall    | 0.923251 |    0.524851 |
| mcc       | 0.659331 |    0.524851 |


## Confusion matrix (at threshold=0.524851)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     695 |                     202 |
| Labeled as DECLINED |                      34 |                     409 |

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
