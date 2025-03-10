#8. For the string "Hello World! Welcome to R programming", write R code to count the number of characters (using
# nchar()) and extract the substring "R programming".

string<-"Hello World! Welcome to R programming"
string
nchar(string)
substring<-substr(string,25,38)
substring