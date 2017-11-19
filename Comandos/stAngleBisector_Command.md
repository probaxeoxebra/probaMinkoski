# stAngle Command

[<b>AngleBisector Command</b> at GeoGebra Manual](https://wiki.geogebra.org/en/AngleBisector_Command)

## stAngleBisector[ <Line>, <Line> ]

Returns both stAngleBisectors of the lines.
Example: AngleBisector(x + y = 1, x - y = 2) yields a: x = 1.5 and b: .

<i> In comparison, the AngleBisector(x + y = 1, x - y = 2) yields a: x = 1.5 and b: y = -0.5. </i>

## stAngleBisector [ <Point>, <Point>, <Point>]

Returns the <b>stAngleBisector</b> of the angle defined by the three points.

Example:
<b>stAngle</b>[Vector[(1, 1)], Vector[(2, 5)]] yields an infinite value in hyperbolic radians. This would create an "error: division by zero" message

<i> In comparison, AngleBisector((1, 1), (4, 4), (7, 1)) yields a: x = 4.</i>

Note: The second point is apex of this stAngle.



Note: See also Mode angularbisector.svg Angle Bisector tool .
