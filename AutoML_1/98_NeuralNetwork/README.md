# Summary of 98_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 64
- **dense_2_size**: 32
- **learning_rate**: 0.05
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

4.3 seconds

## Metric details
|           |    score |      threshold |
|:----------|---------:|---------------:|
| logloss   | 0.335553 | nan            |
| auc       | 0.879714 | nan            |
| f1        | 0.780919 |   0.358924     |
| accuracy  | 0.814925 |   0.358924     |
| precision | 0.788462 |   0.689941     |
| recall    | 1        |   2.67052e-230 |
| mcc       | 0.67993  |   0.358924     |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.335553 |  nan        |
| auc       | 0.879714 |  nan        |
| f1        | 0.780919 |    0.358924 |
| accuracy  | 0.814925 |    0.358924 |
| precision | 0.641509 |    0.358924 |
| recall    | 0.997743 |    0.358924 |
| mcc       | 0.67993  |    0.358924 |


## Confusion matrix (at threshold=0.358924)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     650 |                     247 |
| Labeled as DECLINED |                       1 |                     442 |

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
