# 🧠 Loss
Loss is a numerical metric that describes how wrong a model's predictions are. Loss is a distance so it is always positive.
The goal of training a model is to minimize the loss, reducing it to its lowest possible value.

## 📌 Detailed explaination
In linear regression, there are four main types of loss, which are outlined in the following table:
| Model            | Description | Equation |
|------------------|--------|----------     |
|      $L_1$ loss            | The sum of the absolute values of the difference between the predicted values and the actual values  |  $ ∑\ \lvert actual\ value − predicted\ value \rvert$        | 
| Mean absolute error (MAE)  | The average of $L_1$ losses across a set of N examples  | $ \frac{1}{N} ∑\ \lvert actual\ value − predicted\ value \rvert$          | 
| $L_2$ loss                 | 	The sum of the squared difference between the predicted values and the actual values.  | $ ∑\ (actual\ value − predicted\ value) ^ 2$        | 
| Mean squared error (MSE)   | The average of $L_2$ losses across a set of N examples  |   $ \frac{1}{N} ∑\ (actual\ value − predicted\ value) ^ 2$ | 

## 📌 Choosing a loss
Deciding whether to use MAE ($L_1$) or MSE ($L_2$) can depend on the dataset and the way you want to handle certain predictions.

- MSE moves the model more toward the outliers, while MAE doesn't.

- MSE: The model is closer to the outliers but further away from most of the other data points.

- MAE: The model is further away from the outliers but closer to most of the other data points.