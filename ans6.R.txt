#6. Write R code that calculates the sum of all TRUE values in a given logical vector (using their numeric property
#where TRUE = 1 and FALSE = 0).

log_vec<-c(T,F,T,F,T,T,F,F,F,T,T,F)
log_vec
sum_result<-sum(log_vec)
sum_result