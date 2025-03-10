#16. Create a logical vector and demonstrate the use of the any() and all() functions. Explain, via comments, a scenario
#where any() returns TRUE but all() returns FALSE.

#let a logical vector
log_vect<-c(T,T,T,T,T,T,T,F)
log_vect
any(log_vect)#here any() give true because any one of the value is true
all(log_vect)# it return true when all the values are true
