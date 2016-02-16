# Support-Vector-Machine-Lab
Creation of a support vector machine class.


This is a lab that I worked on while attending BYU.

An SVM class. Upon initialization, it should accept a training data set and training target set.
It should have a method called setKernel which accepts one of the three kernel types, 
and defines a kernel function for the object. It should also have a method to train the classifier, 
and another method to predict the class of a new sample. 
It should predict if x > 0 and if x < 0.


A data set on breast cancer has been provided. 
This is from a breast cancer database from the University of Wisconsin Hospital, Madison, from Dr. W. H. Wolberg.
The attributes are (in order): clump thickness, uniformity of cell size, uniformity of cell shape, 
marginal adhesion, single epithelial cell size, bare nuclei, bland chromatin, 
normal nucleoli, and mitoses, all on a scale from 1 to 10. 
The targets are either 1 or -1, signifying malignant or benign, respectively.



Trained SVMs on the data, trying each kernel with various parameter values. Misclassification rates are supplied.
