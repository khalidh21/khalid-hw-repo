### ***Project 3 Feedback***

***Nico Van de Bovenkamp***

***

**Overall**  
Awesome work on this assignment! You effectively built the models, and interpreted all outputs. As we discussed earlier, what I recommend is that you take this analysis/model, and try your hand using sklearn! Maybe even try out some different types of models we have learned: KNN, Decision trees, random forest, boosted trees, naive bayes, or SVMs!

***Interpreting Odds Ratios***  
Note that Odds Ratios are _not_ percentages, but an interpretation of relative likelihood **given** some probability, or percentage. In other words, when you have an odds ratio of 3.07, then one is 3 times more likely to be have the positive outcome given the condition (3 times more likely to be admitted given in prestife_1). If odds are something like 0.5, then you are **half** as likely to be be admitted given you are in prestige_4. The odds ratio is not quite, "percent chance." Odds ratios are handy for some level of data exploration, and, of course, when it comes to interpreting log odds coefficients. A minor note, but instructive nonetheless. Logistic regression coefficients are not always super informative, and, for the most part, you are often much more concerned with the performance of a model!
