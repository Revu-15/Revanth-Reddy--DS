#15. Write a function that takes a numeric vector and bins the data into three categories: "Low", "Medium", and "High".
#Use the cut() function and return the resulting factor.

numeric_vector <- c(2, 7, 11, 4, 8, 1, 12, 9)

bin_data <- cut(numeric_vector,breaks = c(-Inf, 5, 10, Inf), labels = c("Low", "Medium", "High"))

bin_data
