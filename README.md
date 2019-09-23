# Analyze_A-B_Test_Result

## Introduction
In this project, we gathered an A/B test data conducted by an e-commerce website to determine which page design to chose from two designs. The old design is assigned to a group of people identified to control group, and the new design is assigned to another group called treatment. In this project, we analyzed whether, or not, choosing the second design is of practical significance.
We will Investigate the test data to try to answer the following question:

> Is the proportion of control people who interacted with the old website design more than the proportion of treatment people who interacted with the new website design?

## Assessing
Starting by assessing programmatically, we looked at statistics and characteristics of the data set such as the number
of rows and columns, duplicated data, missing data, and Null-value data. Programmatical assessment is mainly done through pandas, numpy, and matplotlib. The process of assessing checks mainly four elements; completeness, validity, accuracy, consistency. completeness refers to not missing any credential data. Validity refers to the process of recording the data correctly with units. Accuracy relates to how realistic is the data; how is it close to the true value? Finally, consistency is how all the data complement each other to provide a clear picture of the phenomenon. 

## Hypothesis
In this test, the null hypothesis is that the proportion of users who interacted with the control webpage design is equal to or greater than the proportion of interacted treatment users. On the other hand, the alternative hypothesis is that the treatment interaction proportion is not equal to or smaller.
