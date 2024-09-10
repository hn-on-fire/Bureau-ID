# Summary of 54_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 16
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

2.3 seconds

## Metric details
|           |    score |      threshold |
|:----------|---------:|---------------:|
| logloss   | 0.342448 | nan            |
| auc       | 0.877222 | nan            |
| f1        | 0.783002 |   0.390476     |
| accuracy  | 0.821642 |   0.435396     |
| precision | 0.769231 |   0.786417     |
| recall    | 1        |   4.61505e-147 |
| mcc       | 0.680628 |   0.327211     |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.342448 |  nan        |
| auc       | 0.877222 |  nan        |
| f1        | 0.781336 |    0.435396 |
| accuracy  | 0.821642 |    0.435396 |
| precision | 0.656923 |    0.435396 |
| recall    | 0.963883 |    0.435396 |
| mcc       | 0.673272 |    0.435396 |


## Confusion matrix (at threshold=0.435396)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     674 |                     223 |
| Labeled as DECLINED |                      16 |                     427 |

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
