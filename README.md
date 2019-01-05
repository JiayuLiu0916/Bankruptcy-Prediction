Subject:
</br>Predict whether the companies will bankrupt by combining different algorithms with financial data.

Documents description:
</br>"methods used.Rmd" is the code for different algorithms we tried. The algorithms are shown below.
</br>"xgboost tuning.Rmd" is the code for tuning the parameters of Xgboost algorithm.

Software used:
</br> R

Algorithms used:
</br>Logistic regression（AUC result:0.534)
</br>LDA(0.8226)
</br>QDA(0.7556)
</br>SVM with linear kernel(0.8341)
</br>SVM with polynomial kernel(0.709)
</br>SVM with radial kernel(0.8284)
</br>Random forest(0.8876)
</br>Boost(0.8715)
</br>Xgboost(0.9169)

According to the AUC score, we decide to use Xgboost and tune its parameters to get better result.

Public Leaderboard Result:
</br>0.94887
</br>https://www.kaggle.com/c/companies-bankruptcy-forecast/leaderboard

P.S.
</br>After the competition is over, we got better result by tuning the parameters further and achieved our best result 0.94985.
We could also make our results better by using more methods in the process such as variables selection.
