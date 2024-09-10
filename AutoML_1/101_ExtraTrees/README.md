# Summary of 101_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.8
- **min_samples_split**: 20
- **max_depth**: 5
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

2.5 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.406472 |  nan        |
| auc       | 0.878802 |  nan        |
| f1        | 0.784946 |    0.531307 |
| accuracy  | 0.820896 |    0.531307 |
| precision | 0.75     |    0.560806 |
| recall    | 1        |    0        |
| mcc       | 0.683754 |    0.531307 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.406472 |  nan        |
| auc       | 0.878802 |  nan        |
| f1        | 0.784946 |    0.531307 |
| accuracy  | 0.820896 |    0.531307 |
| precision | 0.650817 |    0.531307 |
| recall    | 0.988713 |    0.531307 |
| mcc       | 0.683754 |    0.531307 |


## Confusion matrix (at threshold=0.531307)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     662 |                     235 |
| Labeled as DECLINED |                       5 |                     438 |

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
