#Normal Linear Model (Not clustered)
print("Regular linear model")
Infected <- 2616*47 - 6072  #Predict day 47
for(i in 48:54) {
  Infected <- c(Infected, (2616 * i - 6072 ))
}

#Print predictions
for(i in 1:8){
  stringholder <- sprintf("Date is 03/%i/2020 and there are %i predicted infections.",(7+i),Infected[i])
  print(stringholder)
}

print("======================================================================")

print("Cluster 1 linear model predictions")
#Cluster1
Infected <- 2582 * 23 - 7922  #Predict day 23
for(i in 24:54) {
  Infected <- c(Infected, (2582 * i - 7922 ))
}
#Date 2/13 - 2/29 = 17 days 
for(i in 1:17){ 
  stringholder <- sprintf("Date is 02/%i/2020 and there are %i predicted infections.",(12+i),Infected[i])
  print(stringholder)
}

#Date 3/1 - 3/15 = 15 days 
for(i in 18:32){ 
  stringholder <- sprintf("Date is 03/%i/2020 and there are %i predicted infections.",(i-17),Infected[i])
  print(stringholder)
}

print("======================================================================")

#Cluster2
print("Cluster 2 linear model predictions")
Infected <- 1468 * 37 + 39608  #Predict day 37
for(i in 38:54) { 
  Infected <- c(Infected, (1468 * i + 39608 ))
}
#Date 2/27 - 2/29 = 3 days 
for(i in 1:3){ 
  stringholder <- sprintf("Date is 02/%i/2020 and there are %i predicted infections.",(i+26),Infected[i])
  print(stringholder)
}

#Date 3/1 - 3/15 = 15 days 
for(i in 4:18){ 
  stringholder <- sprintf("Date is 03/%i/2020 and there are %i predicted infections.",(i-3),Infected[i])
  print(stringholder)
}

print("======================================================================")


print("Cluster 3 linear model predictions")
#Cluster 3
Infected <- 2616*47 - 6072  #Predict day 47
for(i in 48:54) {
  Infected <- c(Infected, (2636 * i - 6158 ))
}

#Print predictions
for(i in 1:8){
  stringholder <- sprintf("Date is 03/%i/2020 and there are %i predicted infections.",(7+i),Infected[i])
  print(stringholder)
}

print("======================================================================")

print("death linear model predictions")

#Predict deaths
Death <- 91* 47 - 487 #Predict day 47
for(i in 48:54){
  Death <- c(Death, (91 * i - 487))
}

#Print predictions
for(i in 1:8){
  stringholder <- sprintf("Date is 03/%i/2020 and there are %i predicted infections.",(7+i),Death[i])
  print(stringholder)
}



