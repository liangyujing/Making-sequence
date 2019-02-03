##产生数字 Making sequences

s<- runif(n=100,min=0,max=1)      #等于 <- 0:100定义数量，均匀分布的随机数  #在这里run
s <- rnorm(n=50, mean=10, sd=2)   #定义数量，平均数和标准差，服从正态分布的随机数  
x <- seq(from=1,to=10,by=0.1)     #定义间隔，均匀间隔

# rep
numbers<- c(1,2,3,4)
rep(numbers, c(2,3,4,3))
rep(c(0,1),times=2)   0 1 0 1
rep(c(0,1),each=2)    0 0 1 1
rep(c(0,1),c(4,3))    0 0 0 0 1 1 1
rep(c("cat","dog","pig","spider"),c(1,3,2,1))

# 简单运算
sqrts<- sqrt(s)  开平方根 Create a new variable that is equal to the square root of xxx
