#4. Create a 3×4 matrix from a given logical vector and display the result. Then, create another 3×4 numeric matrix
#and perform an element-wise comparison between them.
logi<-c(T,T,F,F,T,F,F,T,F,T,F,T)
mat_1<-matrix(logi,nrow=3,ncol=4)
mat_1
mat_2<-matrix(c(1,2,3,0,3,0,4,5,1,0,1,0),nrow=3,ncol=4)
mat_2
mat_1==mat_2