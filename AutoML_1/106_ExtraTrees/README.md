# Summary of 106_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.9
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

2.8 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.370241 |  nan        |
| auc       | 0.876993 |  nan        |
| f1        | 0.786618 |    0.560682 |
| accuracy  | 0.825373 |    0.562328 |
| precision | 0.75     |    0.622897 |
| recall    | 1        |    0        |
| mcc       | 0.686974 |    0.553935 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.370241 |  nan        |
| auc       | 0.876993 |  nan        |
| f1        | 0.78453  |    0.562328 |
| accuracy  | 0.825373 |    0.562328 |
| precision | 0.662519 |    0.562328 |
| recall    | 0.961625 |    0.562328 |
| mcc       | 0.677692 |    0.562328 |


## Confusion matrix (at threshold=0.562328)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     680 |                     217 |
| Labeled as DECLINED |                      17 |                     426 |

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
