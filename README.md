# Miscellaneous neuroimaging support scripts

## [Power for Interactions](https://github.com/MRC-CBU/miscellaneous/tree/master/power-for-interactions)

**Is it *really* difficult to detect interactions**


There is a common perception that it is difficult to detect interactions (moderations) in multiple linear regression (MLR). There are several possible reasons for this, but a priori, the power for detecting an interaction is often equivalent to that for detecting a main effect, except in a few special cases, as demonstrated in the notebook and R Markdown code.


## [Relating Age, Brain and Cognition](https://github.com/MRC-CBU/miscellaneous/tree/master/Relating-Age-Brain-and-Cognition)

**A primer on relating Age, Brain and Cognition: As easy as “ABC”.**


A R-markdown script that describes different ways to relate 3 variables, such as Age, Brain and Cognition, for example. It starts with the general linear model (GLM), showing its difficulties in distinguishing underlying models that generate the data, and then shifts to Structural Equation Modelling (SEM) as the solution (since SEM can handle more than one relationship, i.e. more than one “~” in linear model syntax, and then compare models of the data). With SEM, it then demonstrates how to get closer to causal direction (watershed models), how to test mediation effects (e.g., B mediates effect of A on C) and two ways to test moderation effects (e.g., that effect of B on C depends on A). Finally, it introduces latent factors in SEM, and shows how to test for measurement invariance (as an example of multi-group moderation). 


This demo requires a very basic understanding of linear statistical models, but should be a good way to get a basic introduction to SEM for people not familiar with it, and introduce notions like mediation, moderation and measurement invariance.
