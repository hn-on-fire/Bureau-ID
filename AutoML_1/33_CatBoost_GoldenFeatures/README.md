# Summary of 33_CatBoost_GoldenFeatures

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.025
- **depth**: 6
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

3.0 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.32446  | nan           |
| auc       | 0.904268 | nan           |
| f1        | 0.786618 |   0.552071    |
| accuracy  | 0.827612 |   0.59073     |
| precision | 0.8      |   0.688869    |
| recall    | 1        |   0.000783234 |
| mcc       | 0.686974 |   0.473385    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.32446  |   nan       |
| auc       | 0.904268 |   nan       |
| f1        | 0.778098 |     0.59073 |
| accuracy  | 0.827612 |     0.59073 |
| precision | 0.677258 |     0.59073 |
| recall    | 0.914221 |     0.59073 |
| mcc       | 0.661546 |     0.59073 |


## Confusion matrix (at threshold=0.59073)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     704 |                     193 |
| Labeled as DECLINED |                      38 |                     405 |

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
