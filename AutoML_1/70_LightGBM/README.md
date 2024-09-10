# Summary of 70_LightGBM

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: binary
- **num_leaves**: 127
- **learning_rate**: 0.05
- **feature_fraction**: 1.0
- **bagging_fraction**: 1.0
- **min_data_in_leaf**: 50
- **metric**: auc
- **custom_eval_metric_name**: None
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

1.9 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.38142  | nan         |
| auc       | 0.899676 | nan         |
| f1        | 0.786618 |   0.401326  |
| accuracy  | 0.823881 |   0.401326  |
| precision | 0.830769 |   0.661287  |
| recall    | 1        |   0.0889937 |
| mcc       | 0.684756 |   0.401326  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.38142  |  nan        |
| auc       | 0.899676 |  nan        |
| f1        | 0.786618 |    0.401326 |
| accuracy  | 0.823881 |    0.401326 |
| precision | 0.656109 |    0.401326 |
| recall    | 0.981941 |    0.401326 |
| mcc       | 0.684756 |    0.401326 |


## Confusion matrix (at threshold=0.401326)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     669 |                     228 |
| Labeled as DECLINED |                       8 |                     435 |

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
