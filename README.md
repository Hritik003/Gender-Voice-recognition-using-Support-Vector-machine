# Gender-Voice-recognition-using-Support-Vector-machine
Detailed SVM analysis on voice recognition signals
SVM is a Supervised Machine Learning algorithm that separates the points of training data using a Vector/Hyperplane into different classes.
We have implemented it on the Voice Dataset, which we obtained from Kaggle.com.
The dataset has 3168 records classified as male or female with different features obtained from signal processing of the data.
Further, we have compared it with different algorithms to check how feasible it is, And we found that it is one of the best algorithms for this dataset.
Dataset - https://www.kaggle.com/datasets/primaryobjects/voicegender
![Screenshot 2023-07-20 174724](https://github.com/Hritik003/Gender-Voice-recognition-using-Support-Vector-machine/assets/106531948/fe265b71-fe03-4be3-a5e0-a42d5561f215)
Different Kernel Functions, such as the Linear, Polynomial and RBF kernels, have been used for SVM.
Linear Kernel functions: K(Xi,X) = Xi.X
Polynomial kernel function: K(Xi,X) = (k+Xi.X)^r
RBF kernel function: K(Xi,X) = exp{-[k(Xi.Xi) + k(X.X) -2k(Xi.X)]/2ϭ^2)}
