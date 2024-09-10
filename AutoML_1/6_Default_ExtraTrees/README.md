# Summary of 6_Default_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 30
- **max_depth**: 4
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

1.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.435148 |  nan        |
| auc       | 0.875197 |  nan        |
| f1        | 0.781753 |    0.492446 |
| accuracy  | 0.81791  |    0.492446 |
| precision | 0.741935 |    0.531236 |
| recall    | 1        |    0        |
| mcc       | 0.678496 |    0.492446 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.435148 |  nan        |
| auc       | 0.875197 |  nan        |
| f1        | 0.781753 |    0.492446 |
| accuracy  | 0.81791  |    0.492446 |
| precision | 0.647407 |    0.492446 |
| recall    | 0.986456 |    0.492446 |
| mcc       | 0.678496 |    0.492446 |


## Confusion matrix (at threshold=0.492446)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     659 |                     238 |
| Labeled as DECLINED |                       6 |                     437 |

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
