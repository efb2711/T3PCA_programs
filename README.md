# T3PCA_programs
Programs to perform T3-PCA analysis//
Example:
load("SR_data.RData")
source("T3PCAfunc.R")
T3PCAfunc(X3D=data3D_persons_PP,Y=data2D_PP,n=128,m=14,p=11,q=83,r1=6,r2=2,r3=3,conv=.0000001,OriginalAlfa = .5,AlternativeLossF = 1,nRuns = 100,StartSeed=0)
