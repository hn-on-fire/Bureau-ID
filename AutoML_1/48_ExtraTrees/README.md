# Summary of 48_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.9
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

2.0 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.397858 |  nan        |
| auc       | 0.880103 |  nan        |
| f1        | 0.783486 |    0.506229 |
| accuracy  | 0.824627 |    0.51269  |
| precision | 0.705882 |    0.610113 |
| recall    | 1        |    0        |
| mcc       | 0.680951 |    0.42029  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.397858 |   nan       |
| auc       | 0.880103 |   nan       |
| f1        | 0.778928 |     0.51269 |
| accuracy  | 0.824627 |     0.51269 |
| precision | 0.667742 |     0.51269 |
| recall    | 0.934537 |     0.51269 |
| mcc       | 0.665048 |     0.51269 |


## Confusion matrix (at threshold=0.51269)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     691 |                     206 |
| Labeled as DECLINED |                      29 |                     414 |

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
