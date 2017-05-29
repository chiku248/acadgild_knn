# acadgild_knn
assignment knn
#created an ecel file for all the data and imported it to R

> abc <- Book1[1:6,]
> abc

> pqr <- Book1[7:8,]
> pqr

abc_train <- abc[,-3]

> abc_target <- abc
> pqr_test <- pqr[,-3]

> library(class)
model_knn <- knn(train = abc_train, test = pqr_test, abc_target,k=1)


Ans- For X=4 Y=4 value is=B
for X=3.5 Y=3.5 value is A
