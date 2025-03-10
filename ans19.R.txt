#19. Write an R script to compare two strings alphabetically using relational operators. Explain via comments how R
# the order (considering case sensitivity).

string1 <- "apple"
string2 <- "Banana"
print(string1 < string2)  # TRUE if string1 is less than string2

print(string1 > string2)  # TRUE if string1 is greater than string2

print(string1 == string2)  # TRUE if the strings are exactly the same

# Explanation:
# R compares strings based on their ASCII (or Unicode) values.
# The ASCII values for characters are as follows:
# For example, 'a' (ASCII: 97) comes before 'B' (ASCII: 66).
# R considers uppercase letters ('A' to 'Z') to have smaller ASCII values than lowercase letters ('a' to 'z').
# This means 'Banana' is considered "smaller" than 'apple' because 'B' (ASCII 66) comes before 'a' (ASCII 97).
