# Multi-class-classification

We have data from 10 sensors fitted in an industrial plant. There are five classes indicating which product is being produced. The task is to predict the product being produced by looking at the observation from these 10 sensors. Given this, you are expected to implement (a) Bayes’ classifiers with 0-1 loss assuming Normal and exponential (with diagonal co-variances) as class-conditional densities (b) Multi-class Logistic regressor with gradient descent (c)Linear classifier using the one-vs-rest approach. The metrics to be computed are - (a) Classification accuracy, (b) Confusion matrix, (c) Class-wise F1 score, (d) RoC curves for any pair of classes (e) Emipiral risk on the train and test data. DATA: train/test.csv

I have used my hypothesis function as sigmoid here for Bayes’ classifiers with 0-1 loss.
I have used my hypothesis function as softmax here for Multi class Logistic regressor

Roc Curve 1:
----
![Roc Curve 1](https://user-images.githubusercontent.com/101024664/224493027-9d7b5303-edfc-48ba-be4e-6dd036f63e7d.png)
----
Roc Curve 2:
----
![Roc Curve 2](https://user-images.githubusercontent.com/101024664/224493040-a2669ae8-b535-4e01-9de4-7e93daccfe9d.png)
