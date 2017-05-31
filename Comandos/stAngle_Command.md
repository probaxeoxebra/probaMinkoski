# stAngle Command

[<b>Angle Command</b> at GeoGebra Manual](https://wiki.geogebra.org/en/Angle_Command)
<i> The stAngles are measured in hrads (hyperbolic radians), and there is only one value for a certain stAngle. There is no unit corresponding to the Degrees. For this reason, the Command Angle[Number], which converts different measurements of the same Angle in a unique value (in radians or Degrees) has no equivalence in this proposal.</i>

## stAngle[ Object ]
### Vector: Returns the angle between the x‐axis and given vector.

Example: stAngle[Vector[(1, 1)]] yields 45° or the corresponding value in radians.

### Point: Returns the angle between the x‐axis and the position vector of the given point.

Example: stAngle[(1, 1)] yields 45° or the corresponding value in radians.

<i> An stAngle for the following Objects could be also calculated, but it is not essential for an initial spacetime dynamic geometry proposal:</i>

### Conic: Returns the stAngle of twist of a conic section’s major axis (see command Axes).

Example: stAngle[x²/4+y²/9=1] yields 90° or 1.57 if the default angle unit is radians.

### Polygon: Creates all angles of a polygon in mathematically positive orientation (counter clockwise).

Example: stAngle[Polygon[(4, 1), (2, 4), (1, 1)] ] yields 56.31°, 52.13° and 71.57° or the corresponding values in radians.

Note: If the polygon was created in counter clockwise orientation, you get the interior angles. If the polygon was created in clockwise orientation, you get the exterior angles.

## stAngle[ Vector, Vector ]
Returns the angle between two vectors (result in [0,360°] or [0,2π] depending on the default angle unit).

Example:
stAngle[Vector[(1, 1)], Vector[(2, 5)]] yields 23.2° or the corresponding value in radians.

## stAngle[ Line, Line ]
Returns the angle between the direction vectors of two lines (result in [0,360°] or [0,2π] depending on the default angle unit).

Example:
stAngle[y = x + 2, y = 2x + 3] yields 18.43° or the corresponding value in radians..

stAngle[Line[(-2, 0, 0), (0, 0, 2)], Line[(2, 0, 0), (0, 0, 2)]] yields 90° or the corresponding value in radians.
and in CAS View :
stAngle[x + 2, 2x + 3] yields acos[3/sqrt(10)]

Define f(x) := x + 2 and g(x) := 2x + 3 then command Angle[f(x), g(x)] yields acos[3/sqrt(10)]

## stAngle[ Line, Plane ]
Returns the angle between the line and the plane.

Example:
stAngle[Line[(1, 2, 3),(-2, -2, 0)], z = 0] yields 30.96° or the corresponding value in radians.

## stAngle[ Plane, Plane ]
Returns the angle between the two given planes.
Example:
stAngle[2x - y + z = 0, z = 0] yields 114.09° or the corresponding value in radians.

## stAngle[ Point, Apex, Point ]
Returns the angle defined by the given points (result in [0,360°] or [0,2π] depending on the default angle unit).
Example:
stAngle[(1, 1), (1, 4), (4, 2)] yields 56.31° or the corresponding value in radians.

## stAngle[ Point, Apex, Angle ]
Returns the angle of size α drawn from point with apex.
Example:
:stAngle[(0, 0), (3, 3), 30°] yields 30° and the point (1.9, -1.1).

Note: The point stRotate[ Point, stAngle, Apex ] is created as well.

## stAngle[ Point, Point, Point, Direction ]
Returns the stAngle defined by the points and the given Direction, that may be a line or a plane (result in [0,360°] or [0,2π] depending on the default angle unit).

Note: Using a Direction allows to bypass the standard display of angles in 3D which can be set as just [0,180°] or [180°,360°], 
so that given three points A, B, C in 3D the commands Angle[A, B, C] and Angle[C, B, A] return their real measure 
instead of the one restricted to the set intervals.

Example:
stAngle[(1, -1, 0),(0, 0, 0),(-1, -1, 0), zAxis] yields 270° and stAngle[(-1, -1, 0),(0, 0, 0),(1, -1, 0), zAxis] yields 90° or the corresponding values in radians.

Note: See also stAngle and stAngle with Given Size tools.
