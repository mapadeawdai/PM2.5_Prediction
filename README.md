# 2147334 ML&DL Project: PM2.5 Prediction

## Goal and Progress
| Goal  | Progress |
| ------------- |:-------------:|
| Get raw data from the internet with some data processing | Obtained the data from openAQ and open-meteo and merged |
| Random Forest| Implemented and tuned |
| MLP| Have not implemented |
| LSTM| Implemented and tuned |

## Current experiment leaderboard
| Model  | VAL MAE | VAL RMSE | VAL R² |
| ------------- | ------------- | ------------- |:-------------:|
| Persistence | 4.3737 | 6.2416 | 0.8117 |
| Default RF | 4.5794 | 6.6754 | 0.7846 |
| Depth-tuned RF | 4.5157 | 6.5262 | 0.7941 |
| Fully tuned RF | 4.4756 | 6.4100 | 0.8014 |
| Residual RF | 3.9440 | 5.5539 | 0.8509 |
| MLP | Pending | Pending | Pending |
| LSTM: Default | 5.8365 | 8.7083 | 0.6335 |
| LSTM: Tuned | 3.7765 | 4.9436 | 0.8819 |
| LSTM: Dropout | 3.6430 | 4.8519 | 0.8862 |

