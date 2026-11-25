# 2147334 ML&DL Project: PM2.5 Prediction

## Goal and Progress
| Goal  | Progress |
| ------------- |:-------------:|
| Get raw data from the internet with some data processing | Obtained the data from openAQ and open-meteo and merged |
| Random Forest| Implemented and tuned |
| MLP| Have not implemented |
| LSTM| Have not implemented |

## Current experiment leaderboard
| Model  | VAL MAE | VAL RMSE | VAL R² |
| ------------- | ------------- | ------------- |:-------------:|
| Persistence | 4.3737 | 6.2416 | 0.8117 |
| Default RF | 4.5794 | 6.6754 | 0.7846 |
| Depth-tuned RF | 4.5157 | 6.5262 | 0.7941 |
| Fully tuned RF | 4.4756 | 6.4100 | 0.8014 |
| Residual RF | 3.9440 | 5.5539 | 0.8509 |
| Weighted Residual RF | 3.8973 | 5.4708 | 0.8553 |
| Tuned Residual RF | 3.8559 | 5.4231 | 0.8578 |
| Tuned Weighted Residual RF | 3.8372 | 5.3942 | 0.8594 |
| MLP | Pending | Pending | Pending |
| LSTM | Pending | Pending | Pending |

