# proj_3
# project_space
# new line
# I want to be able to edit this space
# so everytime I write something in a new line like this in this space, it will get saved as single line until a new 
# new line
# x*2
((((7+2)*3)-6)/3)
a <- 3
b <- "sky"
c <- c(1, "sky", 3)
roll2 <- function(bones){
  dice <- sample(bones, size = 2, replace = TRUE)
  sum(dice)
}
# here, we modify the dice variable by using vector of probability values that match are synced up to each value of the die vector
roll <- function(){
  die <- 1:6
  dice <- sample(die, size = 2, replace = TRUE,
    prob = c(1/8, 1/8, 1/8, 1/8, 1/8, 3/8))
  sum(dice)
}
#an atomic vector is just a a simple linear vector, or list, of values
# there are 6 types of vectors in R
# doubles, which store regular numbers
die <- c(1:6)
# Integers, which are numbers followed by a capital L. Useful for high precision calculations
int <- c(-1L, 2L, 3L)
# Characters, or non-numeric values. "1" and "one" are both strings because they do not connote a quantity
text<-c("sup", "world")
# Logicals, which are useful for formulas. Apply boolean logic
TRUE
FALSE
# you can give attributes to a vector
die <- c(1:6)
names(die) <- c("one","two","three","four","five","six")

hand2 <- c("ace", "spades", "king", "spades", "queen", "spades", "jack",  "spades", "ten", "spades")
matrix(hand2, nrow = 5, byrow = TRUE)
matrix(hand2, ncol = 2, byrow = TRUE)
card <- c("ace", "spades", 1)
# You can use a List to group together various objects in R, like atomic vectors, 
card <- list("ace", "hearts", 1)
df <- data.frame(face = c("ace"))