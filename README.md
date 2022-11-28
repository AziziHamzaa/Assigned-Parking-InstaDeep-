# Assigned-Parking-InstaDeep-
InstaDeep Coding Interview For Research Internship 
The are n cars located on a 2-dimensional plane at positions (x[i],y[i]) where 0 <= i <= n.
They need to be parked in a straight line parallel to the x-axis with no spaces between them.
The fuel consumed to move a car is abs(x[finish]-x[start]) + abs(y[finish]-y[start]).
Determine the minimum fuel cost to arrange the cars side-by-side in a row parallel to the x-axis.

Exemple:

x = [1,4]

y = [1,4]

One optimal solution is :
* The first car initially at position (1,1) moves to (3,1) for cost of abs(3-1) + abs(1-1) = 2
* The second car initially at position (4,4) moves to (4,1) for cost of abs(4-4) + abs(4-1) = 3

The total fuel consumed is 2 + 3 = 5
