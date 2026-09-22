# bayesian-logistic-regression-mental-health
Bayesian logistic regression analysis of mental health levels using digital behavior and lifestyle factors, with MCMC-based posterior inference, uncertainty quantification, posterior predictive checks, and model comparison.

This project applies Bayesian Logistic Regression to analyze and predict mental health status based on behavioral and lifestyle factors, including age, daily screen time, social media usage, sleep duration, physical activity, anxiety, stress, and mood levels.

The analysis uses JAGS and MCMC to estimate posterior distributions under different prior specifications. Model performance is evaluated using posterior predictive checks, classification accuracy, WAIC, LOO, and DIC, with an additional comparison against classical logistic regression.

Key Results
Bayesian logistic regression with a strongly informative prior achieved WAIC = 27.6, LOOIC = 27.7, and DIC = 36.34.
The Bayesian model with the weakly informative prior achieved 98.98% classification accuracy with a 95% CI of [0.983, 0.994].
Posterior analysis showed different levels of uncertainty across predictors, with age and daily screen time requiring cautious interpretation.
Classical logistic regression was also evaluated using accuracy, odds ratios, confidence intervals, and ROC/AUC analysis.
