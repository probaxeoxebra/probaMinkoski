# stIncircle Command

[<b>Incircle Command</b> at GeoGebra Manual](https://wiki.geogebra.org/en/Incircle%20Command)

<i> Note: an <b>stIncircle</b> is a <b>stCircle</b> (equilateral and straight Hyperbola in the euclidean space) 
which is tangent to the three sides of the triangle (or to their containing straight lines)</i>

### stIncircle[ Point, Point, Point ]
   Returns <b>stIncircle</b> of the triangle formed by the three Points.
   
   Example: 
   
   Let O=(0, 0), A=(3, 0) and B=(0, 5) be three points: 
   
   <b>stIncircle</b>[O, A, B] yields (x - 1.08)² + (y - 1.08)² = 1.18 in Algebra View and 
   
   draws the corresponding <b>stCircle</b> in Graphics View.

## Comments
There are three possible types of <b>stCircles</b> which differ in the value of their <b>stType</b>:
* <b>stType = +1 for spacelike</b> radii (hyperbola with left and right arms)
* <b>stType = -1 for timelike radii</b> (hyperbola with upper and lower arms)
* <b>stType = 0</b> (degenerated case, consisting in two diagonal lines
