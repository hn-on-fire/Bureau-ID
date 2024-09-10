# Summary of 102_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 1.0
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

3.2 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.391964 |  nan        |
| auc       | 0.874017 |  nan        |
| f1        | 0.78733  |    0.540443 |
| accuracy  | 0.824627 |    0.540443 |
| precision | 0.717949 |    0.585284 |
| recall    | 1        |    0        |
| mcc       | 0.686974 |    0.5384   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.391964 |  nan        |
| auc       | 0.874017 |  nan        |
| f1        | 0.78733  |    0.540443 |
| accuracy  | 0.824627 |    0.540443 |
| precision | 0.6571   |    0.540443 |
| recall    | 0.981941 |    0.540443 |
| mcc       | 0.685816 |    0.540443 |


## Confusion matrix (at threshold=0.540443)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     670 |                     227 |
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
