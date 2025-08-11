# 🧠 Linear regression
Linear regression is a type of supervised learning algorithm, its primary function is to fit a linear model to predict numerical values.

## 📌 Detailed explaination
Suppose you want to predict the miles per galon based on a car's heaviness. You would plot a graph with MPG on the y-axis and car's heaviness on the x-axis. You would then fit linear model.  
In ML terms this equation is equivalent to $y' = w_1 * x_1$
- $w_1$ is the weight
- $b$ is the bias

However, if we have multiple features (n) to use to predict our label then our previous equation would then look like: $y' = w_0 * x_0 + w_1 * x_1 +w_2 * x_2...+w_n * x_n + b$


Loss is a numerical metric that describes how wrong a model's predictions are
The goal of training a model is to minimize the loss, reducing it to its lowest possible value
In linear regression, there are four main types of loss, which are outlined in the following table:
| Model            | Description | Equation |
|------------------|--------|----------     |
|      $L_1$ loss            | The sum of the absolute values of the difference between the predicted values and the actual values  | ∑ | actual value − predicted value |        | 
| Mean absolute error (MAE)  | 0.467  | 0.851         | 
| $L_2$ loss                 | 0.499  | 0.834         | 
| Mean squared error (MSE)   | 0.522  | 0.810         | 

