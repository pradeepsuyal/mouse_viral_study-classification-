### mouse viral classification

## Table of CONTENTS 
---------------------
 * [Aim](#aim)
 * [Dataset used](#data)
 * [using SVM](#conclusion)
 

## AIM:<a name="aim"></a>

our goal is to create a classifcation model than predict (given two dosage measurements) if they mouse will still be infected with the virus.

## Dataset Used:<a name="data"></a>

The data shown here simulates a medical study in which mice infected with a virus were given various doses of two medicines and then checked 2 weeks later to see if they were still infected. 

## using SVM for prediction:<a name="conclusion"></a>

**Support Veector Machine**

A support vector machine is a supervised learning algorithm that sorts data into two categories. It is trained with a series of data already classified into two categories, building the model as it is initially trained. The task of an SVM algorithm is to determine which category a new data point belongs in. This makes SVM a kind of non-binary linear classifier.

An SVM algorithm should not only place objects into categories, but have the margins between them on a graph as wide as possible.

Some applications of SVM include:

• Text and hypertext classification

• Image classification

• Recognizing handwritten characters

• Biological sciences, including protein classification

![22](https://miro.medium.com/max/600/1*_RCyhHQw0vNOBFRdQarXkQ.gif)

**choosing rbf as a kernel**

rbf - [Radial Basis Function](https://en.wikipedia.org/wiki/Radial_basis_function_kernel)

When training an SVM with the Radial Basis Function (RBF) kernel, two parameters must be considered: C and gamma. The parameter C, common to all SVM kernels, trades off misclassification of training examples against simplicity of the decision surface. A low C makes the decision surface smooth, while a high C aims at classifying all training examples correctly. gamma defines how much influence a single training example has. The larger gamma is, the closer other examples must be to be affected.

![download](https://user-images.githubusercontent.com/86251750/145720342-7edf58ce-5ebe-492a-a266-0b966e768b7d.png)


**Tools**
-----------------------
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png)  ![seaborn](https://user-images.githubusercontent.com/86251750/132984253-32c04192-989f-4ebd-8c46-8ad1a194a492.png)

