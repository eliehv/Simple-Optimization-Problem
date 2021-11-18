# Simple-Optimization-Problem
modeling problem
* making window area as big as possible is the objective (maximazing the area of window)
on the other hand there are certain amount of materials (12 m) which is the constraint 

  * x[0] is the radius of semicircle and 2*x[0] is one edge of rectangle
  * x[1] is the other edge of rectangle

  * area = (pi*x[0]^2 ) /2  + (2*x[0]*x[1]) 
  * the area must be maximized so, we can minimize -area


  * constraint :
    * pi*x[0] + 2*(2*x[0] + x[1]) = 12 , 

    * x[0] > 0 ,

    * x[1] > 0 
