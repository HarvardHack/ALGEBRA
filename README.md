# ALGEBRA
# WEEK1 HOMEWORK 1

# Q1 68.68407
mean(father.son$sheight)

# Q2 70.54082
mean(father.son$sheight[round(father.son$fheight)==71])

library(dplyr)

filter(father.son,round(fheight)==71) %>% summarize(mean(sheight))

# Q3  Y = a + b^t + e 

# Q4 Between individual variability: people of the same height vary in their weight.

# Q5 225
X[25,3]

#Q6 105
x = 1:10

X=cbind(x, 2*x, 3*x, 4*x, 5*x)

sum(X[7,])

#Q7 matrix(1:60,20,3,byrow=TRUE) 

#Q8 X %*% matrix(1,ncol(X) )

#Q9 -0.8849558

X = matrix(c(3,2,1,5,4,2,-1,0,-5,2,5,0,1,-1,-5,1),4,4)

y = c(10,5,7,4)

sol = solve(X,y)

sol[ 3 ]

# Q10 113

d = a %*% b

d[ 3,2 ]

#Q11 113
sum(a[ 3, ] * b[ ,2 ])


# WEEK 1 HOMEWORK 2

# Q1 5
fitted = X %*% beta

fitted[ 1:2, ]

# Q2 7
fitted = X %*% beta

fitted[ 3:4, ]

# Q3 13
fitted = X %*% beta

fitted[ 3:4, ]

#Q4 7
fitted = X %*% beta

fitted[ 5:6, ]

