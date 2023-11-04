# HW2
### Q6
Obtaining bias and variance error by fitting polynomial with degree $\in$ [1, 3, 8, 15] on X, Y:
* X =  np.arange(-10,10,0.2)
* Y =  $\frac{2 cos(x)}{-\pi} + \frac{x}{pi} + \frac{2 cos(3x)}{-3\pi}$
### Q7
Using Logistic Regression and L2 Regularization to classify points of each below cases:
* case 1:
  * category 1: 200 points restricted to two circles with the same center (1.5, 0) and radii 4 and 9
  * category 2: 200 points within a circle with the center (1.5, 0) and radius 6
* case 2:
  * category 1: 100 points (X, Y) with mean = (1, 0) and std = 1 
  * category 2: 200 points restricted to two circles with the same center (1.5, 0) and radii 2 and 6
### Q8
Implementing non-parametric parzen density estimation (with window size of 20, 50, 100) on duration column of ted_main.csv
