# stCircle Command

[<b>Circle Command</b> at GeoGebra Manual](https://wiki.geogebra.org/en/Circle_Command)

<i> Note: an stCircle has the shape of a (space) Hyperbola wehich is equilateral and whose axes are parallel to the coordinate axes</i>

### stCircle[ Point, Radius Number ]
Yields a <b>stCircle</b> with given center and radius.
### <b>stCircle[ Point, Segment ]</b>
Yields a <b>stCircle</b> with given center and radius equal to the <b>stLength</b> of the given segment.
### <b>stCircle[ Point, Point ]</b>
   Yields a <b>stCircle</b> with given center through a given point.
### <b>stCircle[ Point, Point, Point ]</b>
   Yields a <b>stCircle</b> through the three given points (if they do not lie on the same line).
### <b>stCircle[ Line, Point ]</b>
   Creates a <b>stCircle</b> with line as axis and through the point. 
### <b>stCircle[ Point, Radius, Direction ]</b>
   Creates a stCircle with center, radius, and axis parallel to direction, which can be a line, vector or plane.      
 Example:
    
* <b>stCircle[ Point, Radius, Plane ]</b> yields a stCircle parallel to the plane and with stPerpendicular vector of the plane as axis.

### <b>stCircle[ Point, Point, Direction ]</b>
   Creates a <b>stCircle</b> with center, through a point, and axis parallel to direction.

## Comments
### Tips
* Use <b>stCircles</b> to fix the stDistance between two objects

<b>stCircles</b> are a great way to make the stDistance between two objects constant: 

If there are two points A and B on two lines g (point A) and h (point B) where A can be moved 
and B should have the constant <b>stDistance</b> r to A you can define B as the intersection between the line h 
and the <b>stCircle</b> around A with the radius r. 
As a <b>stCircle</b> intersects a line at two points (in case it's not tangetial or passing by) 
you have to hide & ignore the second intersection. 


    
