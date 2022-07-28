# Bayesian-Analysis-of-Asteroids

There is an infinite number of objects in the outer space. Some of them are closer than we think. Even though we might think that a distance of 70,000 Km can not potentially harm us, but at an astronomical scale, this is a very small distance and can disrupt many natural phenomena.
These objects/asteroids can thus prove to be harmful. Hence, it is wise to know what is surrounding us and what can harm us amongst those.

The objective of the analysis is to discover whether an asteroid is potentially dangerous for the earth or not.
In order to do that, we have different Machine Learning algorithms at our disposal to do binary classification.

The dataset analyzed for this analysis is taken from Kaggle and contains more than 90’000 features regarding 27’000 objects in the space.

Three statistical models for classification are applied: 
-Probit Regression 
-Logistic Regression (with Logit link function) 
-Complementary log-log regression (cloglog) 
The parameters of the models are tuned with Monte Carlo Markov Chain methods, and a fully bayesian in-depth analysis is applied to them. The analysis is divided in 4 parts:
1. Exploratory Data Analysis and Feature Engineering
2. Application of three different statistical models for binomial classification: Probit Regression, Logistic Regression (Logit) and Complementary
log-log Regression. Over these three models, we are gonna observe:
Parameter tuning with Monte Carlo Markov Chain
Visualization of the MCMC with Traceplots, Empirical Average, Density plots, Autocorrelation plots, Correlation matrix of the parameters Model testing on new data
Comparison between Bayesian approach and Frequentist approach for every model
Testing
3. Choice of the best model among the six analyzed
4. Conclusions

