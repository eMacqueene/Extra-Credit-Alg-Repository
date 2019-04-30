# Simpson/Trapezoidal Algorithm
  This algorithm performs integration on a set of tabulated data by using Simpson's 1/3 rule. It makes sure that the x-values are evenly spaced, as the method requires it. Therefore, this is a limitation to the algorithm. 
  Because Simpson's 1/3 rule requires an even number of intervals, the algorithm checks this too. If there are an odd number of intervals between points, one iteration of the trapezoidal integration approximation is used on the last interval, while Simpson's 1/3 is used on the others. 
  Here are the function's inputs:
  1. x = evenly spaced vector with the x-values of the dataset
  2. y = vector holding the y-values of the dataset
  Both vectors must be the same length!
  
  Here are the function's outputs:
  1. I = the approximation of the integral of the tablulated data
