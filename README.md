# VNam-Group-CYS
# PROJECT : Analysing the effect of the CheckYourSmile (CYS) tool

This project is done by : Viet Minh Thong Le & Dinh Triem Phan, a pair of students in 4GMM, INSA Toulouse, scolar year 2019-2020.

## Project Goal
Our objective is to obtain indicators on the plus-value of CYS in a university context and on the combinations of variables needed to obtain the best results and to improve the eﬀects of the tool. 

## Materials
We study a database acquired in three academic years (2016-7, 2017-8 and 2018-9). It contains the evaluation results of students (Snapshot1 and Snapshot2) of diﬀerent courses and the language teaching they received (English or French, engineering courses (CMI), use of CYS) 

## Methods
Descriptive statistics determined the most inﬂuential factors among the variables. Charts such as boxplot illustrated which variables are more important than others. ”interaction.plot” showed how variables interacted mutually.

Linear model [2] reported how multiple variables aﬀected the progression of students simultaneously, including their mutual interactions. Model ANCOVA showed the eﬀect of three qualitative variables and Snapshot1 on Snapshot2.

Non-linear model (decision tree [1]) with the tree graph demonstrated how multiple variables aﬀected the progressions of students. According to cross-validated predictions, we kept the model which possessed the minimal complexity parameters. We studied in two cases the effect of: - 3 qualitative variables on the progression of students as a term of diﬀerence between 2 Snapshots. - 3 qualitative variables and Snapshot1 on Snapshot2 .

## References

[1] R. J. Lewis, An introduction to classiﬁcation and regression tree (cart) analysis, in Annual meeting of the society for academic emergency medicine in San Francisco, California, vol. 14, 2000. 

[2] D. C. Montgomery, E. A. Peck, and G. G. Vining, Introduction to linear regression analysis, vol. 821, John Wiley & Sons, 2012.
