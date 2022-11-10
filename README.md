# AutoML
HHA507_assignment_9

Experiment #1
Data Source:  Healthcare Associated Infections (https://query.data.world/s/lcc3wkldiuom2xid5xlcn3bqpkk263')

Focus on classification (binary or multi-class outcome variable)

Measure ID (categorical)

Compared to National (continuous)

score

The variable tested was score

Per AutoML, the best model was Default_Xgboost

## Metric details
|           |     score |     threshold |
|:----------|----------:|--------------:|
| logloss   | 0.0287939 | nan           |
| auc       | 0.998495  | nan           |
| f1        | 0.984664  |   0.942205    |
| accuracy  | 0.972838  |   0.942205    |
| precision | 1         |   0.999999    |
| recall    | 1         |   9.06675e-08 |
| mcc       | 0.873128  |   0.942205    |

Compared to Baseline, the model performed the best
---------------------------------------------------------------------------------------------------------------------------------------------
2. Experiment #2
Data Source: Life Expectancy (WHO) Statistical Analysis on factors influencing Life Expectancy (LifeExpectancyData.csv)
focus around regression (continuous outcome variable) 

 Country
 
 Adult Mortality
 
 HIV/AIDS
 
 Income composition of resources
 
 Life expectancy
 
The variable tested was Life expectancy

Per AutoML, the best model was the Ensemble

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 1.09375  |
| MSE      | 3.08404  |
| RMSE     | 1.75614  |
| R2       | 0.965513 |
| MAPE     | 0.016699 |

Compared to Baseline, the model performed worse

