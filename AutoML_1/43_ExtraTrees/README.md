# Summary of 43_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
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

1.8 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.380497 |  nan        |
| auc       | 0.87916  |  nan        |
| f1        | 0.788427 |    0.541994 |
| accuracy  | 0.825373 |    0.541994 |
| precision | 0.730769 |    0.617    |
| recall    | 1        |    0        |
| mcc       | 0.687928 |    0.541994 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.380497 |  nan        |
| auc       | 0.87916  |  nan        |
| f1        | 0.788427 |    0.541994 |
| accuracy  | 0.825373 |    0.541994 |
| precision | 0.657617 |    0.541994 |
| recall    | 0.984199 |    0.541994 |
| mcc       | 0.687928 |    0.541994 |


## Confusion matrix (at threshold=0.541994)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     670 |                     227 |
| Labeled as DECLINED |                       7 |                     436 |

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
