#1. Write an R script to create a logical vector of length 12 that alternates between TRUE and FALSE.

logical_vector<-vector("logical",12)
logical_vector[seq(1,12,by=2)]<-TRUE
logical_vector