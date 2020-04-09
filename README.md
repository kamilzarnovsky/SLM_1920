# SLM_1920
Repository for Statistical Learning Methods [223490-0286] - Summer semester 2019/20


---
**Modeling problem report**

Every student will be assigned to one dataset from [UCI Repository](https://archive.ics.uci.edu/ml/datasets.php).
The task is to analyze the data and produce a report with following structure:

`5pts` 1) Introduction, problem description (regression/classification/clustering/etc.), target variable and features explanation

`10pts` 2) Cleaning and preprocessing data - removing or imputing missing data, standarization, one-hot encoding, handling outliers, etc.

`10pts` 3) EDA with focus on exploring relations between features nad target variable

`5pts` 4) Creating models, hyperparameter tuning

`10pts` 5) Graphical and descriptive model assessment

`10pts` 6) Summary, discussion on encountered problems and their solution e.g. how overfitting was avoided or imbalanced data mitigated

Code and descriptions/comments should be in Jupyter or R Markdown notebook. If you wish, you are allowed to choose either R or Python (also remember there is Jupyter kernel for R). Please send reports to _kinga.siuta@gmail.com_ with following naming convention <index_number>_SLM_S1920_Report.< extension > before **10.06.2020r. EOD**. 
  
Each email should have 2 attachments: 
- for Jupyter: `.ipynb` file and `.html/.pdf` file generated from notebook, 
- for R Markdown:  `.Rmd` file and `.html/.pdf` file generated from notebook.

A table of randomly picked datasets below. If someone is missing on the list please contact me. If there is more than one dataset under given hyperlink, pick one.

| Index  | Dataset Name                                        | URL                                                                                          | Data Types                             | Default Task                | Attribute Types             | # Instances | # Attributes |
|--------|-----------------------------------------------------|----------------------------------------------------------------------------------------------|----------------------------------------|-----------------------------|-----------------------------|-------------|--------------|
|    72585    	|    Bank Marketing    	|    https://archive.ics.uci.edu/ml/datasets/Bank+Marketing    	|    Multivariate     	|    Classification     	|    Real     	|    45211    	|    17    |
|    72371    	|    Breast Cancer Wisconsin (Diagnostic)    	|    https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29    	|    Multivariate     	|    Classification     	|    Real     	|    569    	|    32    |
|    88786    	|    Mushroom    	|    https://archive.ics.uci.edu/ml/datasets/Mushroom    	|    Multivariate     	|    Classification     	|    Categorical     	|    8124    	|    22    |
|    72661    	|    Abalone    	|    https://archive.ics.uci.edu/ml/datasets/Abalone    	|    Multivariate     	|    Classification     	|    Categorical, Integer, Real     	|    4177    	|    8    |
|    68734    	|    Wine    	|    https://archive.ics.uci.edu/ml/datasets/Wine    	|    Multivariate     	|    Classification     	|    Integer, Real     	|    178    	|    13    |
|    76417    	|    Forest Fires    	|    https://archive.ics.uci.edu/ml/datasets/Forest+Fires    	|    Multivariate     	|    Regression     	|    Real     	|    517    	|    13    |
|    69501    	|    HTRU2    	|    https://archive.ics.uci.edu/ml/datasets/HTRU2    	|    Multivariate     	|    Classification, Clustering     	|    Real     	|    17898    	|    9    |
|    72439    	|    Student Performance    	|    https://archive.ics.uci.edu/ml/datasets/Student+Performance    	|    Multivariate     	|    Classification, Regression     	|    Integer     	|    649    	|    33    |
|    85456    	|    Polish companies bankruptcy data    	|    https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data    	|    Multivariate     	|    Classification     	|    Real     	|    10503    	|    64    |
|    72514    	|    Musk (Version 2)    	|    https://archive.ics.uci.edu/ml/datasets/Musk+%28Version+2%29    	|    Multivariate     	|    Classification     	|    Integer     	|    6598    	|    168    |
|    105205    	|    Ecoli    	|    https://archive.ics.uci.edu/ml/datasets/Ecoli    	|    Multivariate     	|    Classification     	|    Real     	|    336    	|    8    |
|    64197    	|    QSAR fish toxicity    	|    https://archive.ics.uci.edu/ml/datasets/QSAR+fish+toxicity    	|    Multivariate     	|    Regression     	|    Real     	|    908    	|    7    |
|    68867    	|    BLOGGER    	|    https://archive.ics.uci.edu/ml/datasets/BLOGGER    	|    Multivariate     	|    Classification     	|         	|    100    	|    6    |
|    85292    	|    Drug consumption (quantified)    	|    https://archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29    	|    Multivariate     	|    Classification     	|    Real     	|    1885    	|    32    |
|    84687    	|    Mice Protein Expression    	|    https://archive.ics.uci.edu/ml/datasets/Mice+Protein+Expression    	|    Multivariate     	|    Classification, Clustering     	|    Real     	|    1080    	|    82    |
|    72569    	|    Online News Popularity    	|    https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity    	|    Multivariate     	|    Classification, Regression     	|    Integer, Real     	|    39797    	|    61    |
|    59749    	|    Stock portfolio performance    	|    https://archive.ics.uci.edu/ml/datasets/Stock+portfolio+performance    	|    Multivariate     	|    Regression     	|    Real     	|    315    	|    12    |
|    105260    	|    Residential Building Data Set    	|    https://archive.ics.uci.edu/ml/datasets/Residential+Building+Data+Set    	|    Multivariate     	|    Regression     	|    Real     	|    372    	|    105    |
|    68033    	|    Leaf    	|    https://archive.ics.uci.edu/ml/datasets/Leaf    	|    Multivariate     	|    Classification     	|    Real     	|    340    	|    16    |
|    66149    	|    Divorce Predictors data set    	|    https://archive.ics.uci.edu/ml/datasets/Divorce+Predictors+data+set    	|    Multivariate, Univariate     	|    Classification     	|    Integer     	|    170    	|    54    |
|    102041    	|    Communities and Crime    	|    https://archive.ics.uci.edu/ml/datasets/Communities+and+Crime    	|    Multivariate     	|    Regression     	|    Real     	|    1994    	|    128    |
|    72448    	|    Energy efficiency    	|    https://archive.ics.uci.edu/ml/datasets/Energy+efficiency    	|    Multivariate     	|    Classification, Regression     	|    Integer, Real     	|    768    	|    8    |

---
**Contact**

Name: Kinga Siuta

Email: kinga.siuta@gmail.com

---
**Lecturers**

• lecturer: Bogumił Kamiński

• laboratories: 

Groups 100 and 101 – Michał Kot, 

Group 102 – Kinga Siuta, 

Group 103 - Agata Skorupka, 

Groups 104 and 105 – Łukasz Kraiński

---
**Schedule**

• lectures: Tuesdays, 8:00-10:35, Aula IV

• laboratories: room A-113; Wednesdays 17:10

---
**Lectures**

|Date |Subject|
|-----|-------|
|25-02-20 | Introduction to data science; McKinsey case study|
|03-03-20 | Working with Git and Github|
|10-03-20 | Introduction to Julia programming for data science|
|17-03-20 | Introduction to predictive modeling|
|24-03-20 | Introduction to threading and distributed computing K-nearest neighbors algorithm|
|31-03-20 | Methods of evaluation of predictive model quality|
|07-04-20 | Working with data frames in Julia|
|21-04-20 | Methods of predictive model selection|
|28-04-20 | Regularization for predictive modeling|
|05-05-20 | Introduction to approximation and local predictive models|
|12-05-20 | Introduction to deep learning|
|19-05-20 | Causality modeling: introduction|
|26-05-20 | Causality modeling: algorithms|
|02-06-20 | Storytelling with data|
|09-06-20 | Data science in production environments + written examination|

---
**Laboratories**
|# |Subject|
|--|-------|
|1 |Refresher on R and Python programming|
|2 |Methods of evaluation of classifiers|
|3 |Nonparametric regression models: smoothing spline, LOESS, GAM|
|4 |Classical machine learning models: CART, random forest|
|5 |Deep learning|
|6 |Modeling competition|
|7 |Computer exam|

---
**Literature**

Stephen Boyd and Lieven Vandenberghe, Introduction to Applied Linear Algebra
(http://vmls-book.stanford.edu/)

Gareth J., Witten D., Hastie T., Tibshirani R. (2013), An Introduction to Statistical Learning
with Applications in R (http://www-bcf.usc.edu/~gareth/ISL/)

Hastie T., Tibshirani R., Friedman J. (2013), The Elements of Statistical Learning
(http://www-stat.stanford.edu/~tibs/ElemStatLearn/)

Optional: Kamiński B., Zawisza M. (2012), Receptury w R. Podręcznik dla ekonomisty, Oficyna
Wydawnicza SGH (http://bogumilkaminski.pl/projekty/)

Optional: B. Kamiński, P. Szufel: Julia 1.0 Programming Cookbook, Packt Publishing, 2018
(https://www.packtpub.com/application-development/julia-10-programming-cookbook)

---
**Course evaluation criteria**

<s>• Written examination (50 points); during last lecture; no supporting materials are allowed</s>

• Modeling problem report (50 points); sent to your teaching assistant before last laboratory, subject of modelling should be agreed with teaching assistant

• Laboratory examination (50 points); during last examination; you can bring your own printed
materials

• Possible extra points: homeworks, competition

---
**Grading rules**
|From |To|Final grade|
|-----|--|--------|
|0 |49| 2.0|
|50 |59 |3.0|
|60 |69 |3.5|
|70 |79 |4.0|
|80 |89 |4.5|
|90 |100 |5.0|
