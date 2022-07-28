# Analysis-of-Alternative-Fuel-Vehicle-Adoption-NHTS-Case


The adoption of alternative fuel vehicles is seen as a major step towards  shifting to sustainable energy. This topic is believed to have  wide applications in government policy making and in the automotive manufacturing industry. The objective of this research is to analyze and predict the adoption of AFV using different parametric and non-parametric machine learning models. The results showed that the linear models outperformed the non-parametric models. The best performing models were Logistic Regression, Logistic General Additive Model in addition to the Naive Bayes model, but the latter model had the disadvantage of a lack of interpretability.


Main Challenges faced in this project was the unbalanced dataset, where the individuals that adopt an AFV vehicle only represent ~4 % of the total observations. To solve this problem, I applied Synthetic Minority Over Sampling Technique SMOTE for numerical and categorical features in order to create artificial observations and this technique help in increasing the predictive performance. On top on that, that dataset contains big number of categorical features which could lead to a challange in the factor analysis process. This challenge was addressed by applying Factor Analysis of Mixed Data FAMD.
