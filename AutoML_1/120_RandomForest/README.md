# Summary of 120_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.9
- **min_samples_split**: 40
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

2.8 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.321337 |  nan        |
| auc       | 0.90358  |  nan        |
| f1        | 0.786618 |    0.539883 |
| accuracy  | 0.829851 |    0.611645 |
| precision | 0.846154 |    0.699238 |
| recall    | 1        |    0        |
| mcc       | 0.684756 |    0.539883 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.321337 |  nan        |
| auc       | 0.90358  |  nan        |
| f1        | 0.772455 |    0.611645 |
| accuracy  | 0.829851 |    0.611645 |
| precision | 0.692308 |    0.611645 |
| recall    | 0.873589 |    0.611645 |
| mcc       | 0.650502 |    0.611645 |


## Confusion matrix (at threshold=0.611645)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     725 |                     172 |
| Labeled as DECLINED |                      56 |                     387 |

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
