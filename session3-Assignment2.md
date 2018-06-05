

# Acadgild-Dataanalytics-session3-Assignment21,




1,Define matrix mymat by replicating the sequence 1:5 for 4 times and transforming into a matrix, sum over rows and columns.



b<-matrix(rep(1:5), nrow=5, ncol=4);b
colSums(b)
rowSums(b)





> b<-matrix(rep(1:5), nrow=5, ncol=4);b
     [,1] [,2] [,3] [,4]
[1,]    1    1    1    1
[2,]    2    2    2    2
[3,]    3    3    3    3
[4,]    4    4    4    4
[5,]    5    5    5    5

> colSums(b)
[1] 15 15 15 15

> rowSums(b)
[1]  4  8 12 16 20
