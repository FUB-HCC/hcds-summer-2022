**ReadME: A3-Reproducibility**

Course: Human-centered Data-Science (Prof. Claudia Müller-Birn)
Teacher: Lars Sipos
Student researcher: Laura-Sophia von Hirschhausen
Freie Universität Berlin, summerterm 2022

Assignment 3 is divided into two topics: (3.1) _reproducible model training_ of the [southern german credit dataset](https://archive.ics.uci.edu/ml/datasets/South+German+Credit), and (3.2) _reproducing results_ of [Verma & Rubin (2018)](https://dl.acm.org/doi/10.1145/3194770.3194776) using the [german credit dataset](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)). 

For 3.1. we will follow the _reproducible workflow_ stages that were presented during the lecture. The codesheet is documented and can stand alone. If you want to dive deeper into the workflow you may have a look at the notebook _reproducible workflow_ in this folder. The central questions we asked when working on the data analysis are stated and answered.

The preprocessing of the dataset has been done in Assignment 2. Firstly it was done for the German Credit Dataset. Form there some problems with the dataset occured. IF you want more information on that you may check the folder A2_Data. Therefore the preprocessing has been done in the same way for the South German Credit Dataset, which you can also find in the folder A2_Data.

For 3.2. we tried to reproduce the results of the paper, following a quote of the paper on the steps that the authors have been doing in their analysis: For our discussion, we trained an off-the-shelf logistic regression classifier in Python. We applied the ten-fold cross-validation technique, using 90% of the data for training and the remaining 10% of the data for testing and illustrating each of the definitions. We used numerical and binary attributes directly as features in the classification and converted each categorical attribute to a set of binary features, arriving at 48 features in total. (Verma & Rubin, 2018)

Spoiler alarm! 

For this codesheet it was not possible to reproduce the results of the authors, and a short discussion of this is found as documentation of the code. The work of Verma & Rubin is professionally done and there may be many reasons why the results couldn't be reproduced. Furthermore, one has to keep in mind that the approach of the paper of Verma & Rubin was not on reproducibility, but on addressing fairness-related issues. 

Matter of fact, the reader is very welcome to use this code in order to reproduce the results or to optimize the data analysis by a differen modeling. If you do so and want to reach out to the author of this codesheet you can do that via the following canals: 
E-Mail: _laurasophia.vonhirschhausen@gmail.com_
LinkedIN: _https://www.linkedin.com/in/laura-von-hirschhausen/_

Please don't hesitate to reach out also if you find conceptual mistakes or odd interpretation! Everyone is happy to learn from others. 

Have a good time with the code and a steep learning curve!


**Repository structure** 

codesheet 						A3_Reproducibility.ipynb
codetable (South German Credit Data)			codetable.txt
German Credit Data human readable dataset		df_germanData_readable.csv
German Credit Data original dataset			gc_data.csv
South German Credit Data preprocessed data 		south_german_credit_data_preprocessed.csv		
