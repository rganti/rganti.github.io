---
title: "Deep Learning for Time Series Forecasting"
excerpt: "Applying methods developed in machine translation and language modeling to accurately forecast stock prices <br/><img src='/images/QQQ_Results.jpg'>"
collection: portfolio
---

Using deep learning methods developed in the field of machine translation, it is possible to achieve high accuracy forecasts of stock prices. The model was trained on pricing data from 2020-08-01 to 2021-02-01 and validated from 2021-02-01 to 2021-03-01. In the plot below, we observe that initially, after training for approximately 10 epochs, 1-minute ahead forecasts of QQQ are not very accurate (green line). Accuracy gradually increases as training continues for 80 epochs and both the training and validation loss decrease. Eventually, we observe that it is possible for the model to accurately forecast out of sample on the test set (purple line).

<img src='/images/QQQ_Results.jpg'>
