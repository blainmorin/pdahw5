# pdahw5

1. Write a bootstrap algorithm to adjust for optimism on training data in using forward
and backward stepwise regression to select a best model for predicting GFR. Carry
out the following algorithm
(a) Find forward and backward regression to the entire dataset and compute R2
train.
(b) Bootstrap the data 1000 times and fit forward and backward regression models
to each bootstrap, saving R2
boot train.
(c) For each bootstrap sample, calculate R2
boot test on the part of the original training
set not selected into the bootstrap.
(d) Calculate R2
boot opt = R2
boot train − R2
boot test. This is the apparent optimism in
the bootstrap sample
(e) Average R2
boot opt across the bootstrap samples. This is the average optimism
(f) Subtract the average R2
boot opt from R2
train to get an estimate of test R2
.
2. Use cross-validation to construct a predictive model with a) stepwise regression; b)
ridge regression; c) lasso regression. At the end, refit using the best fitting model
of each type on the whole dataset. Compare the estimate of test R2 between the
bootstrap approach and the stepwise, ridge and lasso approaches.
3. Describe the findings of the different models in clearly written text, tables and figures
discussing both the differences between the model findings and consistencies. Which
factors are predictive? How well do the models predict the outcomes?
