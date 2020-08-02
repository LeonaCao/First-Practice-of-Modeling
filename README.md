# First-Trial-of-Modeling
This is an extra assignment right after assignment 1 dealing with data with time series and weather. In this script I also did some visualizations.

But the most important part is modeling. In terms of the predictive variables, I created both polynomial and log features. 
And then I used them along with the original X data to build and fit ElasticNet models with varying alpha values. 

Finally, I also built and fitted ElasticNet models for only the original X data with varying alpha values, 
and compared the best fitted model to the one with polynomial and log features to see whether those newly 
created features helped improve the model performance.
