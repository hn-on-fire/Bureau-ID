# Summary of 129_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.9
- **min_samples_split**: 20
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

2.9 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.41171  |  nan        |
| auc       | 0.874949 |  nan        |
| f1        | 0.777385 |    0.43696  |
| accuracy  | 0.81194  |    0.43696  |
| precision | 0.711111 |    0.567572 |
| recall    | 1        |    0        |
| mcc       | 0.673582 |    0.43696  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.41171  |   nan       |
| auc       | 0.874949 |   nan       |
| f1        | 0.777385 |     0.43696 |
| accuracy  | 0.81194  |     0.43696 |
| precision | 0.638607 |     0.43696 |
| recall    | 0.993228 |     0.43696 |
| mcc       | 0.673582 |     0.43696 |


## Confusion matrix (at threshold=0.43696)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     648 |                     249 |
| Labeled as DECLINED |                       3 |                     440 |

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
