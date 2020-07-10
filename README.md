# HumanActivityRecog
Detect the type of activity performing by a human subject by using his/her smartphone sensors. 

![alt text](https://miro.medium.com/max/700/1*EvxO1sdZ1DCLfDxQNTiflQ.png)

## About The Project

### Problem Statement
Domain experts from the field of Signal Processing collects the data from Accelerometer and Gyroscope of Smartphone. They break up the data in the time window of 2.56 seconds with 50% overlapping i.e., 128 reading

They engineered 561 features from each time window of 2.56 seconds.

By using either human engineered 561 feature data or raw features of 128 reading, our goal is to predict one of the six activities that a Smartphone user is performing at that 2.56 Seconds time window

## Approach

1) We will apply classical Machine Learning models on these 561 sized domain expert engineered features.

2) As we know that LSTM works well on time-series data, so we have decided that we will apply LSTM of Recurrent Neural Networks on 128 sized raw readings that we               obtained from accelerometer and gyroscope signals.

### Built With
```sh
 python
 sklearn
 Dask
 matplotlib
 seaborn
 folium
```
<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
Data Source: https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones
