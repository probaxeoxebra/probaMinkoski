# stAngle Command

[<b>Angle Command</b> at GeoGebra Manual](https://wiki.geogebra.org/en/Angle_Command)

<i> The <b>stAngles</b> are measured in hrads (<b>hyperbolic radians</b>), and there is only one value for a certain <b>stAngle</b>. There is no unit corresponding to the Degrees. For this reason, the  <b>Angle[Number] Command</b>, which converts different measurements of the same Angle in a unique value (in radians or Degrees) has no equivalence in this proposal.</i>

[The value of a stAngle is a measure of an Area](https://github.com/probaxeoxebra/probaMinkoski/blob/master/documents/stAngles.pdf)

[General stAngles have Complex Values](https://github.com/probaxeoxebra/probaMinkoski/blob/master/documents/ComplexstAngles.pdf)

## stAngle[ Object ]
### Vector: Returns the <b>stAngle</b> between the x‐axis and given vector.

Examples: 
<b>stAngle</b>[Vector[(1, 1)]] yields an infinite value in hyperbolic radians. This would create an "error: division by zero" message

<i> In comparison, the Angle[Vector[(1, 1)]] Command yields 45° or the corresponding value of 0.7854 radians.</i>

<b>stAngle</b>[Vector[(2, 1)]] yields a value of 0.5493 in hyperbolic radians. 
<i> In comparison, Angle[Vector[(2, 1)]] yields 0.4636 in radians.</i>

### Point: Returns the <b>stAngle</b> between the x‐axis and the position vector of the given point.

<b>stAngle</b>[(1, 1)] yields an infinite value in hyperbolic radians. This would create an "error: division by zero" message

<i> In comparison, Angle[(1, 1)] yields 45° or the corresponding value of 0.7854 radians.</i>

<b>stAngle</b>[(2, 1)] yields a value of 0.5493 in hyperbolic radians. 
<i> In comparison, Angle[(2, 1)] yields 0.4636 radians.</i>

### Polygon: Creates all <b>stAngle</b> of a polygon in mathematically positive orientation (counter clockwise).

Example: <b>stAngle</b>[Polygon[(4, 1), (2, 4), (1, 1)] ] yields 0.8047, 1.1513 and 0.3466 in  <b>hyperbolic radians</b>.
<i> In comparison, Angle[Polygon[(4, 1), (2, 4), (1, 1)] ] yields 0.9828, 0.9098 and 1,2491 in radians.</i>

Note: If the polygon was created in counter clockwise orientation, you get the interior angles. If the polygon was created in clockwise orientation, you get the exterior angles.

### Conic: Returns the <b>stAngle</b> of twist of a conic section’s major axis (see command Axes).
<i> This  <b>stAngle</b>  for Conics could be also calculated, but it is not essential for an initial spacetime dynamic geometry proposal:</i>

## stAngle[ Vector, Vector ]
Returns the <b>stAngle</b> between two vectors 

Example:
<b>stAngle</b>[Vector[(1, 1)], Vector[(2, 5)]] yields an infinite value in hyperbolic radians. This would create an "error: division by zero" message

<i> In comparison, Angle[Vector[(1, 1)], Vector[(2, 5)]] yields 23.2° or the corresponding value of 0.4049 in radians.</i>

<b>stAngle</b>[Vector[(2, 3)], Vector[(2, 5)]] yields a value of 0.3811 in hyperbolic radians. 

<i> In comparison, Angle[Vector[(2, 3)], Vector[(2, 5)]] yields 11.89° or the corresponding value of 0.2075 in radians.</i>


## stAngle[ Line, Line ]
Returns the <b>stAngle</b> between the direction vectors of two lines 

Example:
<b>stAngle</b>[y = 3x + 2, y = 2x + 3] yields a value of 0.2027 hyperbolic radians.

<i> In comparison, Angle</i>[y = 3x + 2, y = 2x + 3] yields 8.13° or the corresponding value of 0.1419 radians.

<b>stAngle</b>[Line[(-2, 0, 0), (0, 0, 3)], Line[(2, 0, 0), (0, 0, 3)]] yields a value of 1.609 hyperbolic radians.

<i> In comparison, Angle</i>[Line[(-2, 0, 0), (0, 0, 3)], Line[(2, 0, 0), (0, 0, 3)]] yields 90° or the corresponding value of 1.57 radians.

and in CAS View :
<b>stAngle</b>[3x + 2, 2x + 3] yields acos[7/sqrt(50)]

<i> In comparison, Angle</i>[3x + 2, 2x + 3] yields acos[3/sqrt(10)]

Define f(x) := 3x + 2 and g(x) := 2x + 3 then command <b>stAngle</b>[f(x), g(x)] yields acos[7/sqrt(50)]

<i> In comparison, command Angle</i>[f(x), g(x)] would yield in this same case acos[3/sqrt(10)]

## stAngle[ Line, Plane ]
Returns the <b>stAngle</b> between the line and the plane.

Example:
<b>stAngle</b>[Line[(1, 2, 3),(-2, -2, 0)], z = 0] yields 0.693 hyperbolic radians.

<i> In comparison, Angle</i>[Line[(1, 2, 3),(-2, -2, 0)], z = 0] yields 30.96° or the corresponding value of 0.54 radians.

## stAngle[ Plane, Plane ]
Returns the <b>stAngle</b> between the two given planes.

Example:
<b>stAngle</b>[2x - y + z = 0, z = 0] yields 0.4812 hyperbolic radians.

<i> In comparison, Angle</i>[2x - y + z = 0, z = 0] yields 114.09° or 2.005 radians.

## stAngle[ Point, Apex, Point ]
Returns the <b>stAngle</b> defined by the given points 
Example:
<b>stAngle</b>[(1, 1), (1, 4), (4, 2)] yields 0.8047 hyperbolic radians.

<i> In comparison, Angle</i>[(1, 1), (1, 4), (4, 2)] yields 56.31° or 0.983 radians.

## stAngle[ Point, Apex, Angle ]
Returns the <b>stAngle</b> of size α drawn from point with apex.
Example:
<b>stAngle</b>[(0, 0), (3, 3), 0.5236] yields 0.5236 hyperbolic radians and the point (-2.064 , -2.064  ).

<i> In comparison, Angle</i>[(0, 0), (3, 3), 30°] yields 30° (0.5236 rads) and the point (1.9, -1.1).

Note: The point stRotate[ Point, stAngle, Apex ] is created as well.



Note: See also <b>stAngle</b> and <b>stAngle with Given Size</b> tools.
