# Discussion questions

1. Consider two regression models:

    Model 1: Y ~ X1 + X2
    Model 2: Y ~ X1 + X2 + X3 + X4 + X5 + X6

*   Why might Model 2 almost always fit the training data better?
*   Why might Model 1 sometimes perform better under cross-validation?
*   What does this tell us about the relationship between model flexibility and generalization?

2. Cross-validation assumes that the model has no access to information from the test fold during training. If cross-validation is designed to simulate predicting new data, what kinds of decisions in your data processing and analysis pipeline might accidentally allow the model to “see” the data it is supposed to predict? Could leakage occur even if you never explicitly look at the test data?
