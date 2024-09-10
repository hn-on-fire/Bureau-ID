# Summary of 46_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.8
- **min_samples_split**: 50
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

2.2 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.436375 | nan           |
| auc       | 0.871274 | nan           |
| f1        | 0.779267 |   0.482756    |
| accuracy  | 0.815672 |   0.482756    |
| precision | 0.725    |   0.53843     |
| recall    | 1        |   8.98443e-05 |
| mcc       | 0.674282 |   0.482756    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.436375 |  nan        |
| auc       | 0.871274 |  nan        |
| f1        | 0.779267 |    0.482756 |
| accuracy  | 0.815672 |    0.482756 |
| precision | 0.64497  |    0.482756 |
| recall    | 0.984199 |    0.482756 |
| mcc       | 0.674282 |    0.482756 |


## Confusion matrix (at threshold=0.482756)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     657 |                     240 |
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
