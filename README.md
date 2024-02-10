# Relationship Success Factor Analysis

This project analyzes quantitative data to identify key factors that contribute to long-lasting romantic relationships.
We focus specifically on understanding how the context of how couples originally met influences the longevity of their relationship,
and how their attributes affect the success in the relation.

The analysis relies on the results of the survey [How Couples Meet and Stay Together (HCMST)](https://data.stanford.edu/hcmst).
The dataset contains responses from a nationally representative sample of 4,002 American adults on how they met their romantic partners, with follow-up data on relationship outcomes; the data provides insights into relationship origins and quantitative factors impacting couple success and longevity. 

By applying statistical analysis and machine learning approaches, we explore the following questions:

- To what extent does how couples meet influence their relationship outcome? 
- Which variables are most predictive of relationship success and longevity?


## Overview of the methodology

To prepare the dataset for analysis and modeling, we employ techniques like correlation analysis for feature selection, and principal component analysis for
dimensionality reduction. This helped us reduce the number of varialbes down to 56, from 725.

For modeling relationship outcomes, we primarily leverage regression approaches including linear regression, LASSO regression, and random forest regression to quantify the influence of different factors and predict relationship longevity. These approaches help identify the most salient variables and quantify their effects.

We utilize correlation matrices as baseline models to understand the power of the regression methods.

Together, these methods enable us to effectively analyze the dataset, select important features, build predictive models, and derive data-driven insights to answer our key research questions around relationship success factors. The combination of machine learning and statistical analysis provides a robust quantitative approach.