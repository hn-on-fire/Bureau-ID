# Summary of 4_Default_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 16
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

2.3 seconds

## Metric details
|           |    score |      threshold |
|:----------|---------:|---------------:|
| logloss   | 0.338853 | nan            |
| auc       | 0.882991 | nan            |
| f1        | 0.779385 |   0.382706     |
| accuracy  | 0.81791  |   0.382706     |
| precision | 0.769231 |   0.667308     |
| recall    | 1        |   3.17878e-242 |
| mcc       | 0.674282 |   0.316349     |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.338853 |  nan        |
| auc       | 0.882991 |  nan        |
| f1        | 0.779385 |    0.382706 |
| accuracy  | 0.81791  |    0.382706 |
| precision | 0.650075 |    0.382706 |
| recall    | 0.972912 |    0.382706 |
| mcc       | 0.672064 |    0.382706 |


## Confusion matrix (at threshold=0.382706)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     665 |                     232 |
| Labeled as DECLINED |                      12 |                     431 |

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
