# stIncircle Command

[<b>Incircle Command</b> at GeoGebra Manual](https://wiki.geogebra.org/en/Incircle%20Command)

<i> Note: an <b>stIncircle</b> is a <b>stCircle</b> (equilateral and straight Hyperbola in the euclidean space) 
which is tangent to the three sides of the triangle (or to their containing straight lines)</i>

### stIncircle[ Point, Point, Point ]
   Returns <b>stIncircle</b> of the triangle formed by the three Points.
   
   * [Trial Version with GeoGebra Applet](https://ggbm.at/RD4JnUnR)
   
   Left part: construction of the stBisector Tool, Right Part: stInCircle for an arbitrary Triangle.
   
   Note: Drag the Vertexes of the Triangle and move the slider until the stCircle is tangent to all the sides (or their prolongued lines).
   
   The colours of the stBisectrices explain their stType, and the stCircles try to match them.
   
   Example: 
   
   Let O=(0, 0), A=(3, 0) and B=(0, 5) be three points: 
   
   <b>stIncircle</b>[O, A, B] yields  (x - 1.25)² - (y - 1.25)² = (+/-)1.25² in Algebra View and 
      
   draws the corresponding two Orthogonal <b>stCircles</b> in Graphics View.
   
   ![stIncircle_Test](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Comandos/Images/Mink_stlIncircle_Test.JPG)
   
   <i> Note: The (euclidean) Incircle of the same triangle yielded the (circle) equation (x - 1.08)² + (y - 1.08)² = 1.18   </i> 
   
   ![Eucl_Incircle_Test](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Comandos/Images/EuclIncircle_Test.JPG)
   
   
## Comments
There are three possible types of <b>stCircles</b> which differ in the value of their <b>stType</b>:
* <b>stType = +1 for spacelike</b> radii (hyperbola with left and right arms)
* <b>stType = -1 for timelike radii</b> (hyperbola with upper and lower arms)
* <b>stType = 0</b> (degenerated case, consisting in two diagonal lines

See also: [stCircle Command](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Comandos/stCircle_Command.md)
