# Summary of 124_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 64
- **dense_2_size**: 16
- **learning_rate**: 0.08
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

3.4 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.348863 | nan           |
| auc       | 0.870594 | nan           |
| f1        | 0.772052 |   0.323901    |
| accuracy  | 0.808955 |   0.646266    |
| precision | 0.730769 |   0.661959    |
| recall    | 1        |   5.29144e-71 |
| mcc       | 0.666781 |   0.323901    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.348863 |  nan        |
| auc       | 0.870594 |  nan        |
| f1        | 0.768535 |    0.646266 |
| accuracy  | 0.808955 |    0.646266 |
| precision | 0.641026 |    0.646266 |
| recall    | 0.959368 |    0.646266 |
| mcc       | 0.653027 |    0.646266 |


## Confusion matrix (at threshold=0.646266)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     659 |                     238 |
| Labeled as DECLINED |                      18 |                     425 |

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
