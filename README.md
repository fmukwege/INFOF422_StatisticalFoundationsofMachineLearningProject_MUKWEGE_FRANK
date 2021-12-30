## Project done in the context of a machine learning course INFOF422 : Statistical Foundations of Machine Learning 

(Link to course URL : https://www.ulb.be/en/programme/info-f422)

# Final grade of the project : 9/10. Final grade on the course : 14/20.


# The goals of the project are:
• To participate to the "Pump it Up: Data Mining the Water Table" DrivenData competition by imple-
menting and assessing different supervised learning algorithms and different methods of feature se-
lection in the related classification task.
• to select among the learning and feature selection techniques the ones which appear to be the most
accurate and use them for submitting to the DrivenData competition.
• to report your analyses and results as a Jupyter notebook.

DrivenData competition
The goal of the competition is to improve maintenance operations of water pumps and ensure that clean,
potable water is available to communities across Tanzania. In order to achieve that, a smart understanding
of which waterpoints will fail is required. Your objective is to build a predictive model which is able to
correctly predict which pumps are functional, which need some repairs, and which don’t work at all, using
data from Taarifa and the Tanzanian Ministry of Water. The model has to be trained using the Training set
values, Training set labels files available on the DrivenData platform (see Figure 1), it includes roughly 60000
labeled samples and 40 features. The students should then predict the labels for the samples included in
the Test set values, and submit them to the platform following the provided Submission format. The students
should register using its ULB/VUB netid as username and accept the rules of the competition (notably no
hidden additional accounts).

# Project 2020-2021

The team of 3 students was asked to :
1. implement in the R language a pipeline for data preprocessing, including missing value imputa-
tion, normalization (if required), feature engineering and feature selection. This procedure must be
detailed in the notebook. The text must contain the list of relevant/selected variables and the mo-
tivation of their choice. The use of visualizations and tables to provide a better understanding of
the data and the usage of formulas and pseudo-code to describe the feature selection procedure is
strongly encouraged. Note one third of the score will be attributed on the basis of the quality of the
documentation. (3 points)
2. implement in the R language a model selection procedure. This procedure must be detailed in the
notebook and exclusively use the packages listed in Section 5. The text must mention the different
-2/4-INFO-F-422 - Statistical foundations of machine learning
Project 2020-2021
Specifications
(and at least three) models (among those presented during the course) which have been taken into
consideration and the procedure used for model assessment and selection. The use of figures, formu-
las, tables and pseudo-code to describe the model selection procedure is strongly encouraged. Note
one third of the score will be attributed on the basis of the quality of the documentation.(3 points)
3. implement a learning procedure using other R packages than the ones listed in Section 5 . This
procedure must differ from the one in the previous point in terms of the classification model (e.g.
a deep learning model, a gradient boosting tree) and/or the feature selection strategy. A procedure
combining multiple models is also allowed, provided that it integrates at least a learner different
from the ones presented in the practicals. This procedure must be detailed in the notebook. The text
should justify the choice of this procedure, assess its accuracy with respect to the one developed in
the point 2 and discuss the results. The use of figures, formulas, tables and pseudo-code to describe
the combination of this novel procedure is strongly encouraged. Note one third of the score will be
attributed on the basis of the quality of the documentation.(3 points)
4. On the basis of the procedure described in the previous steps the team must compute the predictions
for the competition and submit them via the DrivenData website. The name of the team should
appear in the official leaderboard of the competition. The link to enrol in the DataDriven competition
is available here. (1 point)

## I focused on the second and third part. 

## Specifications
The team has to choose a learning method and a feature selection method among at least three alternatives.
For the learning method (at point 2.), the only packages that may be used are those included in this list :
• stats/ridge (linear/ridge models)
• nnet (neural networks)
• tree/rpart (decision trees)
• randomForest (random forest)
• RSNNS (radial basis functions)
• lazy (nearest neighbours)
• e1071 (SVM)
• glmnet (LASSO/ElasticNet models)

For the point 3. the team is free to employ other learning methods, either already available online, or
coded. The quality of the classification models during the selection process should be assessed by using
classification accuracy. The report must be an R Jupyter notebook which has to specify and justify (with
tables, figures) the selection procedures which led to the final choice. The team has to return, together
with the report, the datasets employed in the notebook, the set of predictions submitted to the DrivenData
competition and a video summarizing the whole predictive procedure.

