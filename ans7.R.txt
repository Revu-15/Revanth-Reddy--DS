#7. Given a numeric vector, write R code to extract all elements that are greater than 10 using logical subsetting.

num_vector<-c(6,2,10,7,14,9,23,67,19,4)
num_vector
lg_vec<-num_vector>10
lg_vec
num_vector[lg_vec]