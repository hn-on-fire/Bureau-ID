# Summary of 130_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.9
- **min_samples_split**: 20
- **max_depth**: 6
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

3.1 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.379551 |  nan        |
| auc       | 0.873672 |  nan        |
| f1        | 0.779152 |    0.419599 |
| accuracy  | 0.814925 |    0.547994 |
| precision | 0.738462 |    0.607539 |
| recall    | 1        |    0        |
| mcc       | 0.676756 |    0.419599 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.379551 |  nan        |
| auc       | 0.873672 |  nan        |
| f1        | 0.766478 |    0.547994 |
| accuracy  | 0.814925 |    0.547994 |
| precision | 0.657512 |    0.547994 |
| recall    | 0.918736 |    0.547994 |
| mcc       | 0.643901 |    0.547994 |


## Confusion matrix (at threshold=0.547994)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     685 |                     212 |
| Labeled as DECLINED |                      36 |                     407 |

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
