Some feedback:
Q3.1: When calculating odds ratios of an event, it should simply be the (#of successes/# of failures). In our instance, given a prestige of 1, 33 people got accepted, and 28 were not. Therefore the odds are 33/28 = 1.17 <br>
Q3.2: 94/245  =.383 <br>
Q4.4: The odds ratio can be computed by raising e to the power of the logistic regression coefficients. Therefore, you can run np.exp(result.params) and you'll get the odds for each of the variables. <br>