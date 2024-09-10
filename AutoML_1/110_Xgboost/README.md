# Summary of 110_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.15
- **max_depth**: 5
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
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.32441  | nan           |
| auc       | 0.896498 | nan           |
| f1        | 0.78481  |   0.463851    |
| accuracy  | 0.825373 |   0.559478    |
| precision | 0.846154 |   0.779812    |
| recall    | 1        |   0.000696988 |
| mcc       | 0.683104 |   0.0736634   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.32441  |  nan        |
| auc       | 0.896498 |  nan        |
| f1        | 0.766467 |    0.559478 |
| accuracy  | 0.825373 |    0.559478 |
| precision | 0.686941 |    0.559478 |
| recall    | 0.866817 |    0.559478 |
| mcc       | 0.64085  |    0.559478 |


## Confusion matrix (at threshold=0.559478)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     722 |                     175 |
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
