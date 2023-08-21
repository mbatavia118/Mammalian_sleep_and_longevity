# Mammalian_sleep_and_longevity
Course project for Linear Models, Spring 2022

Authors: Mariska Batavia, Jack Donohue, Rowdy Dudley

Mammalian Sleep and Longevity: An Analysis of the mammalsleep Data Set

Daily sleep duration and longevity are important aspects of mammalian biology, and are factors that affect, and are affected by, many other physiological, life history, and ecological traits. Both daily sleep duration and longevity may be hard to accurately measure in practice, due to the logistical constraints inherent in capturing, housing, and/or monitoring rare or non-domesticated species. In this project we sought to model these traits as a function of other, potentially more easily measurable features of species.

Our data for this project came from the mammalsleep data set from the Faraway package in R. This dataset contains data on 62 species of mammals, and includes measures of brain and body mass, lifespan, gestation, daily sleep duration, and three categorical indicies (predation, exposure, and danger indices) that capture various aspects of a species’ behavioral ecology. We sought to build models that could predict daily sleep duration and odds of being longliving as accurately as possible, and also wanted to understand the relationship between these outcomes and various predictor variables.

Over the course of the project, we built three models. The first model used multiple linear regression to model daily sleep duration, treating the three categorical indices as additional quantitative variables in the model, rather than as categories. The second model used multiple linear regression to model daily sleep duration, but unlike the first approach, treated the three categorical indices as categorical variables. This second approach generated a better model than the first approach. Our third model used logistic regression to model the odds of being longliving (defined as the top 25% of lifespans).

Complete details can be found in the final report and code is visible in the R Markdown file.
