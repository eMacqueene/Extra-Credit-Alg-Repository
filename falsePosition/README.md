# False Position Algorithm

This algorithm uses the iterative False Position method to estimate the root of a given function. 
It ensures that the user correctly brackets the root by presenting an error if the upper and lower limits do not bracket it. It also has a default stopping criteria of 0.0001 if the stopping criteria is not specified by the user. 

The user inputs are:
1. func = the function of which the root is being estimated
2. xl = the lower limit of the initial bracket
3. xr = the upper limit of the initial bracket
4. es = specified stopping criteria (defaults to 0.0001 if not given)

The outputs are:
1. root = the estimate of the root
2. ea = the approximate error
3. fx = the value of the function at the estimated root
4. iter = the number of iterations the program used
