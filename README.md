# CZ4041-Machine-Learning

## Store Item Demand Forecasting
Kaggle Project Link: [Store Item Demand Forecasting](https://www.kaggle.com/c/demand-forecasting-kernels-only/overview)  

## Problem Statement
For this task, we are given 5 years of sales figures for items sold by different stores. And we are asked to predict the next 3 months of sales for different items sold by different stores. 

This task is essentially a time series forecasting problem. It is a regression problem as well as we are predicting numerical sales figures in the upcoming months. On a high level, we have to look at how past sales figures can reflect certain trends that allow us to forecast a sales figure for a certain item sold by a certain store. 

## Models Employed

### 1. LightGBM model
This is an efficient boosting model developed by Microsoft. It consists of an ensemble of decision tree models. The code for it can be found in the LightGBM.ipynb notebook.

### 2. CNN-LSTM model
This is a deep learning model that combines the strengths of both a Convolutional Neural Network (CNN) and Long short-term memory (LSTM). It uses the CNN for feature extraction followed by the LSTM for the training on the dataset. The code for this mode can be found in the CNN_LSTM.ipynb notebook.

### 3. CNN model
This is a pure CNN model. It is composed mainly of 3 layers - the convolution layer, pooling layer, and fully connected layer. The code for it can be found in the PureCNN.ipynb notebook.

## Models Performance
### LightGBM
| Private LeaderBoard      | Public Leaderboard |
| ----------- | ----------- |
| Score: 12.87223      | Score: 14.15129       |
| Rank: Top 29.4%  | Rank: Top 40.7%        |

### CNN-LSTM
| Private LeaderBoard      | Public Leaderboard |
| ----------- | ----------- |
| Score: 12.92530     | Score: 14.03768      |
| Rank: Top 34.2%  | Rank: Top 32.46%       |

### CNN
| Private LeaderBoard      | Public Leaderboard |
| ----------- | ----------- |
| Score: 36.59492     | Score: 14.92425      |
| Rank: Top 93%  | Rank: Top 61.4%      |

*Note: The submissions for the LightGBM, CNN-LSTM, and CNN models can be found in the submission_LightGBM.csv, submission_CNN_LSTM.csv, and submission_CNN.csv files respectively.*

## Team Members
* Jonathan Chang Ji Ming	
* Jordan Tan Rei Yao	
* Lai Ming Hui
* Lynn Enhua Masillamoni	


