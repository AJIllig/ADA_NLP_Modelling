README
The purpose of the files included here is to provide an example of my coding style and organisation, in both Python and R. Included are sandbox versions to show the developement phase as well as the final submitted version and report.
The pdf report and Jupyter Notebook files are unaltered copies of project work completed in late November, 2018, for the Applied Data Analysis graduate unit I undertook at Monash University. As such, the format here meets the requirements of the intensive course, as well representing the learning and application of new and old material.
PROJECT OVERVIEW
For this project, I was provided a training set of 106.5k source-unknown texts, each assigned one of 24 classifications (C1 - C24), on which to perform data wrangling and modelling for the purpose of predicting the classifications of a smaller test set of unclassified texts. 
Part 1: Data Wrangling in Python - This included cleaning the training set using Natural Language Processing methods, identifying and isolating the components unique to each training class, and then applying identical processing to the test set. Vectorized forms of the training and test sets were then created to pass on to the modelling phase.
Part 2: Modelling in R - The cleaned training set was split into sub-train and sub-test sets and used to train several multinomial classification models, including naive Bayes, logistic regression, linear discriminant analysis, linear support vector machine, k-clustering, and others. K-fold cross-validation and parameter tuning were included for models that supported them. The most successful model was identified as having the highest accuracy for predicting the sub-test set classifications. That model was then used to assign classifications to the true test set.
A summary pdf report discussing model selection and tuning, the final R program containing only the chosen model, and a text file listing the test set classifications were then submitted. The Python preprocessing was not part of the required submission.
OUTCOME
The submitted test set classifications were then compared to the true classifications by the unit intructor. Students were ranked by prediction accuracy (I placed 4 of 33).
INCLUDED FILES
Python_PreProcessing_v3.ipynb 
R_Modelling_v3.ipynb
R_Modelling_Final.ipynb
Summary_Report.pdf
EXCLUDED FILES - training and test sets, vectorized sets, test set classifications

