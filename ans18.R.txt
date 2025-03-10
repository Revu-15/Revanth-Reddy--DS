#18. Given a numeric vector, write R code to create a new vector where all values less than the mean of the vector are
#replaced with NA.

num_vec<-c(51,6,22,31,8,9,14,25)
num_vec
mean_value<-mean(num_vec)
num_vec[num_vec<mean_value]<-NA
num_vec