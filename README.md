# MSc-Data-Science-Summer-Project
Predicting yellow cards from football data, with data supplied by SmartOdds UK. 

In this project, I 
* Research on literature surrounding yellow cards, factors that influence the awarding of cards such as referee bias, home effects, Covid-19 etc. I also look at some common models used in Football statistical modelling.

* Conduct exploratory analysis, to understand the marginal bivariate distributions of interest with yellow card counts. This can be crucial in informing model choice, such as linear models. This was also important to reveal a distinct nature of the data, which is high cardinality of variables, namely teams and referee.

* Chose models based on their strengths with respect to the nature of the data. Model fitting and basic evaluation was done, although the crux was in the final comparison of all models, through the use of a test set. Models used include: linear, generalised linear models, mixed effects, GEE, tree-based random forest and gradient boosted models, and finally an interesting application of a GPBoost model which specifically targets high cardinality data.

* PCA to tackle high mutlicollinearity, to see if it improved the application of linear models, which can be detrimentally affected by it. Also helps to reduce dimensionality.

* Explored possible limitations of models and data. 
