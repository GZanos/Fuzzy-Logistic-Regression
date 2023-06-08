# Fuzzy-Logistic-Regression
A Robust Fuzzy Logistic Regression Framework Against Imbalance and Separation

Link to article:

We propose a new fuzzy logistic regression framework with robust characteristics against imbalance and separation while keeping the interpretability of classical 
logistic regression. Separation and imbalance are two core problems in logistic regression which can result in biased coefficient estimates and inaccurate predictions. 
Existing research on fuzzy logistic regression primarily focuses on developing possibilistic models instead of using a logit link function that converts log-odds ratios 
to probabilities, while little consideration is given towards issues of separation and imbalance. Our study aims to address these challenges by proposing new methods of 
fuzzifying binary variables and classifying subjects based on a comparison against a fuzzy threshold. We explore the use of different combinations of fuzzy and crisp predictors, 
output and coefficients to understand which combinations perform better under different conditions of imbalance and separation. Three optimization and four performance 
measures are used to optimize the coefficient estimates and assess the classification accuracy by the proposed fuzzy logistic regression framework. Numerical experiments 
with simulated and real datasets are conducted to demonstrate the usefulness and superiority of the proposed framework. Seven crisp machine learning models are also 
implemented for benchmarking in the numerical experiments. The proposed framework shows consistently strong performance results across datasets with imbalance or separation 
issues and performs equally well when such issues are absent. Meanwhile, the considered machine learning methods are significantly impacted by the imbalanced datasets with 
varied performance results. Our fuzzy logistic regression framework effectively addresses separation and imbalance issues, outperforming traditional crisp machine learning 
models in varied scenarios.

Our recommendation is:
* For imbalanced data, use Case II or Case III.
* If your data has singificant separation present, use Case IV.
* If there are no separation or imbalance issues, Cases II and III perform best.
