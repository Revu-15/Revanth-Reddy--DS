#11. Given the string "apple, apple, and apple", write R code that uses sub() to replace only the first occurrence of
#"apple" with "orange", and gsub() to replace all occurrences.

string <-"apple, apple, and apple"
string
ssa<-sub("apple","orange",string)
ssa
gga<-gsub("apple","orange",string)
gga