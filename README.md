# TEST

df<-Exam.Dataset
IT <-integer()
for (i in 1:173){
  if (df[i,56] == "IT"){ 
  IT[i]<- 1
  }else{
  IT[i]<--1
  }
}
