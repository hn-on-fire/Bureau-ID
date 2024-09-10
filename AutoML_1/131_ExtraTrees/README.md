# Summary of 131_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: gini
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

3.2 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.413097 |  nan        |
| auc       | 0.877734 |  nan        |
| f1        | 0.784629 |    0.511687 |
| accuracy  | 0.820149 |    0.511687 |
| precision | 0.777778 |    0.55472  |
| recall    | 1        |    0        |
| mcc       | 0.683801 |    0.511687 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.413097 |  nan        |
| auc       | 0.877734 |  nan        |
| f1        | 0.784629 |    0.511687 |
| accuracy  | 0.820149 |    0.511687 |
| precision | 0.649408 |    0.511687 |
| recall    | 0.990971 |    0.511687 |
| mcc       | 0.683801 |    0.511687 |


## Confusion matrix (at threshold=0.511687)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     660 |                     237 |
| Labeled as DECLINED |                       4 |                     439 |

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
