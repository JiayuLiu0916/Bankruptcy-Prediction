Subject:
Predict whether the companies will bankrupt by combining different algorithms with financial data.

Documents description:
"methods used.Rmd" is the code for different algorithms we tried. The algorithms are shown below.
"xgboost tuning.Rmd" is the code for tuning the parameters of Xgboost algorithm.

Software used:
</br> R

Algorithms used:
Logistic regression（AUC result:0.534)
LDA(0.8226)
QDA(0.7556)
SVM with linear kernel(0.8341)
SVM with polynomial kernel(0.709)
SVM with radial kernel(0.8284)
Random forest(0.8876)
Boost(0.8715)
Xgboost(0.9169)

According to the AUC score, we decide to use Xgboost and tune its parameters to get better result.

Public Leaderboard Result:
0.94887
https://www.kaggle.com/c/companies-bankruptcy-forecast/leaderboard

P.S.
After the competition is over, we got better result by tuning the parameters further and achieved our best result 0.94985.
We could also make our results better by using more methods in the process such as variables selection.
