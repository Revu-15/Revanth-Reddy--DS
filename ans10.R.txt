#10. Write an R script that demonstrates the difference between cat() and paste() by printing the same set of words
#using both functions with a custom separator.

result1<-paste("data","science","R",sep="@")
result1

result2<-cat("data","science","R",sep="~")
result2