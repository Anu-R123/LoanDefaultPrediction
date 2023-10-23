# LoanDefaultPrediction
Home Equity Loan Default Prediction - Decision Trees

**Problem**
Retail banks lend home loans and the interest they earn is a significant portion of their profit and income, so selecting and approving the loan is a judicious process that is time-consuming and requires detailed analysis of credit score and other financial details and there is a human-bias component. By relying on advancements in AI, it is possible to create a model to predict between default and non-default borrowers using classification.

The intended goal is to effectively detect defaulters (based on existing credit history) to increase profits for the bank (or avoid losses). Using the provided dataset with existing customers, one can extract features that would be beneficial to determine whether a new customer will default on the loan. The predictive model must be explainable so that justifications can be provided in case of future disputes.

**Proposed solution design** 
The proposed solution design is to implement an XGBoost (Extreme Gradient Boosting) Classification model for this loan default prediction project. The reason this model is very effective while compared with other models from this notebook are:

After some hyperparameter tuning, it can be seen that Precision and Recall are 0.95% and 0.84% respectively, indicating this model can sucessfully detect defaulting. In addition, the accuracy is 93%, this model clearly outperfomed other models tuned.
There are some distinct advantages to XG boost that make it a great choice:

It supports L1 and L2 regularisation which helps in preventing overfitting as well as pruning.
This model is known to be stable even with sparse data and for its high performance
Trees are built in parallel (rather than sequentially) which is computationally efficient
