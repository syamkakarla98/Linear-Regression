# [Linear Regression Using Python](https://en.wikipedia.org/wiki/Linear_regression)

[![Python 3.6](https://img.shields.io/badge/python-3.6-green.svg)](https://www.python.org/downloads/release/python-360/)

## Click [here](https://github.com/syamkakarla98/Linear-Regression/releases) to download the code.

### Prerequisites

The things that you must have a decent knowledge on: 
```
    * Python
    * Linear Algebra
    * Calculus
```

### Installation

* This project is fully based on python. So, the necessary modules needed for computaion are:
```
    * Numpy
    * Sklearn
    * Matplotlib
    * Pandas
```
* The commands needed for installing the above modules on windows platfom are:
```python

    pip install numpy
    pip install sklearn
    pip install matplotlib
 
```
* we can verify the installation of modules by  importing the modules. For example:
```python

    import numpy
    from sklearn.decomposition import kernelPCA 
    import matplotlib.pyplot as plt
    
```
### Explanation 

* Here were performing **linear regression** on the Boston house pricing dataset.
* The details of the dataset are:
  1. Title: Boston Housing Data

  2. Sources:
    (a) Origin:  This dataset was taken from the StatLib library which is
                maintained at Carnegie Mellon University.
    (b) Creator:  Harrison, D. and Rubinfeld, D.L. 'Hedonic prices and the 
                 demand for clean air', J. Environ. Economics & Management,
                 vol.5, 81-102, 1978.
    (c) Date: July 7, 1993

  3. Past Usage:
   -   Used in Belsley, Kuh & Welsch, 'Regression diagnostics ...', Wiley, 
       1980.   N.B. Various transformations are used in the table on
       pages 244-261.
    -  Quinlan,R. (1993). Combining Instance-Based and Model-Based Learning.
       In Proceedings on the Tenth International Conference of Machine 
       Learning, 236-243, University of Massachusetts, Amherst. Morgan
       Kaufmann.

  4. Relevant Information:

      Concerns housing values in suburbs of Boston.

  5. Number of Instances: 506

  6. Number of Attributes: 13 continuous attributes (including "class"
                         attribute "MEDV"), 1 binary-valued attribute.

  7. Attribute Information:

      1. **CRIM**      per capita crime rate by town
      2. **ZN**        proportion of residential land zoned for lots over 25,000 sq.ft.
      3. **INDUS**     proportion of non-retail business acres per town
      4. **CHAS**      Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
      5. **NOX**       nitric oxides concentration (parts per 10 million)
      6. **RM**        average number of rooms per dwelling
      7. **AGE**       proportion of owner-occupied units built prior to 1940
      8. **DIS**       weighted distances to five Boston employment centres
      9. **RAD**       index of accessibility to radial highways
      10. **TAX**      full-value property-tax rate per $10,000
      11. **PTRATIO**  pupil-teacher ratio by town
      12. **B**        1000(Bk - 0.63)^2 where Bk is the proportion of black by town
      13. **LSTAT**    % lower status of the population
      14. **MEDV**     Median value of owner-occupied homes in $1000's

    8. Missing Attribute Values:  None.

* Click here to find the program [LinearRegression_BOSTON_Dataset.py](https://github.com/syamkakarla98/Linear-Regression/blob/master/LinearRegression_BOSTON_Dataset.py)

### Result:

* The above program results a scatter plot showed below:
    
    ![lin_reg_boston](https://user-images.githubusercontent.com/36328597/43992265-c0a304ca-9d31-11e8-89d3-931ca3e3227f.png)
    
* The output of the program is showed below:

    ![lin_reg_boston_output](https://user-images.githubusercontent.com/36328597/43992266-c0ddbc78-9d31-11e8-83bb-7076dafc4526.PNG)

 
#### click here to see the program [LinearRegression_DIABETES_Dataset.py](https://github.com/syamkakarla98/Linear-Regression/blob/master/LinearRegression_DIABETES_Dataset.py) implementing linear regression on Diabetes dataset.


### Conclusion 

   * Performed **Linear Regression** on BOSTON house pricing and Diabetes dataset.
   

## License

This project is licensed under the **MIT** License - see the [LICENSE.md](https://github.com/syamkakarla98/Linear-Regression/blob/master/LICENSE.md)
