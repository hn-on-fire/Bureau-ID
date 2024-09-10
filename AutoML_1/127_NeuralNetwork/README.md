# Summary of 127_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 32
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

4.1 seconds

## Metric details
|           |    score |      threshold |
|:----------|---------:|---------------:|
| logloss   | 0.347366 | nan            |
| auc       | 0.8743   | nan            |
| f1        | 0.775693 |   0.564808     |
| accuracy  | 0.813433 |   0.582388     |
| precision | 0.769231 |   0.78834      |
| recall    | 1        |   3.68252e-129 |
| mcc       | 0.670408 |   0.505211     |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.347366 |  nan        |
| auc       | 0.8743   |  nan        |
| f1        | 0.77396  |    0.582388 |
| accuracy  | 0.813433 |    0.582388 |
| precision | 0.645551 |    0.582388 |
| recall    | 0.96614  |    0.582388 |
| mcc       | 0.662545 |    0.582388 |


## Confusion matrix (at threshold=0.582388)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     662 |                     235 |
| Labeled as DECLINED |                      15 |                     428 |

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
