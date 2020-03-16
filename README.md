# 102architect
second EPITECH math project made in Python.


SUBJECT :

You are working on a homeplanning software for an architecture firm. The goal is to simplify the process of
drawing the plan, and to integrate various features such as scale management, changing the point of view,
moving doors and windows along walls. . .

You are in charge of implementing the geometric transformations (rotation to change point of view, translation to move an object, scaling to zoom in and out, reflection
and any combination of these transformations).
You need to develop a program to compute the coordinates of a point after several transformations. To
make it nice and clean, you chose to use homogeneous coordinates. O being the origin of both axis, here
are the transformations to be implemented:

  • Translation,
  
  • Scaling,
  
  • Rotation centered at O,
  
  • Reflection over any axis that passes through O,
  
  • Any combination of the previous transformations.
  

USAGE :

    ./102architect x y transfo1 arg11 [arg12] [transfo2 arg12 [arg22]] ...
    
DESCRIPTION

  x abscissa of the original point
  
  y ordinate of the original point
  
  transfo arg1 [arg2]
  
    -t i j translation along vector (i, j)
    
   -z m n scaling by factors m (x-axis) and n (y-axis)
   
    -r d rotation centered in O by a d degree angle
    
   -s d reflection over the axis passing through O with an inclination
   
   angle of d degrees
