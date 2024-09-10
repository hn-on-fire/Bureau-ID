# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                      |   Weight |
|:---------------------------|---------:|
| 12_Xgboost                 |        1 |
| 32_CatBoost                |        2 |
| 32_CatBoost_GoldenFeatures |        1 |
| 35_RandomForest            |        8 |
| 61_CatBoost                |        2 |
| 73_Xgboost                 |        1 |
| 85_CatBoost                |        3 |
| 88_CatBoost                |        1 |
| 98_NeuralNetwork           |        1 |

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.327484 | nan          |
| auc       | 0.911784 | nan          |
| f1        | 0.786618 |   0.594052   |
| accuracy  | 0.838806 |   0.618769   |
| precision | 0.903846 |   0.671741   |
| recall    | 1        |   0.00160579 |
| mcc       | 0.686974 |   0.520295   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.327484 |  nan        |
| auc       | 0.911784 |  nan        |
| f1        | 0.784431 |    0.618769 |
| accuracy  | 0.838806 |    0.618769 |
| precision | 0.703041 |    0.618769 |
| recall    | 0.887133 |    0.618769 |
| mcc       | 0.669805 |    0.618769 |


## Confusion matrix (at threshold=0.618769)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     731 |                     166 |
| Labeled as DECLINED |                      50 |                     393 |

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
