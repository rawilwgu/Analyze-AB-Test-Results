# Analyze-AB-Test-Results
Analyzing A/B test results within python.

## Requirements

pandas
numpy
random
matplotlib
statsmodels

## Part I - Descriptive Statistics

In this section, we read in the dataset and view the various aspects of the dataset. Asking questions such as, "How many rows have missing values?" or "How many customers are from specific countries?"
We view the types of columns, as well as confirm the dataset is in the correct format for analysis.

## Part II - Probability

In this section, we calculate several different probabilities to compare to later on. We calculate the probability of conversion based on the control and treatment group data. 
We calculate the probability of conversion based on which country they are listed from. Then we fill in the conversion rates for all countries.

## Part III - Experimentation

In this section, we create samples and simulate the conversion rates, then plot the results based on the means of the simulations.

## Part IV - Algorithms

In this section, we establish that we will use logistic regression and use statsmodels to create a logistic model. Then we view the summary of the model. 
We finally confirm that the country is statistically significant in predicting the conversion rate.
