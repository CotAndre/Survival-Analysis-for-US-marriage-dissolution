# Survival_Analysis_for_US_marriage_dissolution
Survival analysis is the set of statystical methods to analyze survival data, that means data in which we have a time-to-event column (survival time) and an event column (binary or categorical). Each istance in the dataset has the possibility to reach the event ("failured" istance) or not ("censored" istance). Also the dataset is described by a set of "covariates", or features, who characterize different individuals in the population.

The reasons why we are interested in performing a survival analysis can be different, mainly this methods are used for the following purposes:
- Studying the dataset in terms of survival function and hazard function to estimate the survival probability of a group of individuals;
- Verify if different groups of individuals are statistically equivalent wrt to time to event;
- Making predictions on survival time;
- Understanding which covariates bring much probability to occuring the event for a sample of individuals;

In this work, i performed a survival analysis on US couples marriage dissolution, with the aim to understand in which cases there's a high probability to failure (divorce), and to discover which covariates are more correlated to the target variable.

Data can be found here:
