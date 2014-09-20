eigen-ridge
===========

L2-regularized (ridge) linear regression without intercept in c++11 as Eigen3 template function.
Uses SVD decomposition, works with both tall and wide design matrices.

This is free and unencumbered software released into the public domain.

```c++
#include "eigen_ridge.hpp"

MatrixXd A;
VectorXd y;
auto x = ridge(A, y, alpha);
```
