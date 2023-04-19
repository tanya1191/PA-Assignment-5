# Parameter_Optimization_of_SVM
## Assignment 5 for UCS654 Predictive Analysis

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, Nu,epsilon and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

In this python file, I've used a Fitness Function to optimize the parameters.

## Parameters Optimized
The following parameters are optimized in this project:

1.nu(C): the parameter that controls the number of support vectors used in the model.

2,kernel: the kernel function used for the SVM algorithm.

3.epsilon(gamma): the margin of error allowed in the SVM algorithm.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/EEG+Eye+State

The data set consists of 14 EEG values and a value indicating the eye state.

Number of Instances: 14980 

Number of Attributes: 15

# Final Result Table
![image](https://user-images.githubusercontent.com/76492020/233191945-c1b284cb-e765-4381-851c-f99ed9869b2b.png)

# Convergence Graph
<img width="649" alt="image" src="https://user-images.githubusercontent.com/76492020/233193984-8faa5c4e-5b1c-4067-92d3-33db2ecac8f1.png">

# Result

The best parameters of SVC for the given dataset are:

Kernel : rbf

Nu : 0.18

Epsilon : 0.69

The above parameter gave a maximum accuracy of 0.88.
