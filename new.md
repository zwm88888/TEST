
a<-reg2$coefficients[1]
b<-reg2$coefficients[2]
xhat<-a+b*1225
CI_high<-xhat+1.96*17.39925
CI_low<-xhat-1.96*17.39925
Con_interval<-c(CI_low,CI_high)
