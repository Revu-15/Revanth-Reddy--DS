#3. Given two numeric vectors of equal length, write R code to check if they are element-wise equal and then output
#the indices where they differ using the which() function.

n_vec1<-c(2,4,6,7,9,4,88)
n_vec2<-c(2,4,8,7,4,1,88)
n_vec1==n_vec2

which(n_vec1!=n_vec2)