#13. Create a factor from the vector c("Jan", "Mar", "Feb", "Apr", "May", "Dec", "Nov") and order the factor to reflect
#the natural calendar order (January to December). Display the ordered factor.

month <- c("Jan", "Mar", "Feb", "Apr", "May", "Dec", "Nov")

month_order <- c("Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec")

month_factor <- factor(month, levels = month_order, ordered = TRUE)

print(month_factor)
