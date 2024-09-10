# Summary of 81_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.8
- **min_samples_split**: 50
- **max_depth**: 7
- **eval_metric_name**: auc
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

2.6 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.380457 |  nan        |
| auc       | 0.878936 |  nan        |
| f1        | 0.785331 |    0.506198 |
| accuracy  | 0.820896 |    0.506198 |
| precision | 0.738462 |    0.617688 |
| recall    | 1        |    0        |
| mcc       | 0.684841 |    0.506198 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.380457 |  nan        |
| auc       | 0.878936 |  nan        |
| f1        | 0.785331 |    0.506198 |
| accuracy  | 0.820896 |    0.506198 |
| precision | 0.65037  |    0.506198 |
| recall    | 0.990971 |    0.506198 |
| mcc       | 0.684841 |    0.506198 |


## Confusion matrix (at threshold=0.506198)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     661 |                     236 |
| Labeled as DECLINED |                       4 |                     439 |

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
