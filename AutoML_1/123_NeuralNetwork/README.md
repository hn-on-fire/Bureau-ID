# Summary of 123_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 64
- **dense_2_size**: 16
- **learning_rate**: 0.01
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

5.2 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.389694 | nan         |
| auc       | 0.886236 | nan         |
| f1        | 0.777385 |   0.0227692 |
| accuracy  | 0.821642 |   0.518088  |
| precision | 0.788462 |   0.91788   |
| recall    | 1        |   0         |
| mcc       | 0.673582 |   0.0227692 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.389694 |  nan        |
| auc       | 0.886236 |  nan        |
| f1        | 0.764532 |    0.518088 |
| accuracy  | 0.821642 |    0.518088 |
| precision | 0.678322 |    0.518088 |
| recall    | 0.875847 |    0.518088 |
| mcc       | 0.63791  |    0.518088 |


## Confusion matrix (at threshold=0.518088)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     713 |                     184 |
| Labeled as DECLINED |                      55 |                     388 |

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
