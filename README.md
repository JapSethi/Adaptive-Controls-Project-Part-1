# Adaptive-Controls-Project-Part-1

Steps taken to develop a MRAC controller for my Reduced 1st Order System:
- Finding the reduced 1st Order equation and replacing coefficents with constant star elements
-
- Specifying the Desired trajectory and finding it's derivative
- Writing the equation of reference trajectry with reference controller element (r)
- Writing the Reference Error dynamics (er) equation and it's derivative, and equating it to eventually find the reference controller element (r)
- Writing Error Dynamics Equation for later use in simulink blocks (e)
- Finding the controller with star elements
- Closing the loop to use the controller and thus finding the controller's star coefficients (theta_x and theta_r)
Note: THe above steps are all used to make it MRC, we can further make some changes as below to make it MRAC
- We can further make it adaptive by replace the star coefficients with adaptive elements a(t) and b(t)
- Find an appropriate Lyapunov Function and it's derivative
