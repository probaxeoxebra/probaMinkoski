# stAngleBisector Command

[<b>AngleBisector Command</b> at GeoGebra Manual](https://wiki.geogebra.org/en/AngleBisector_Command)

## stAngleBisector[ Line, Line ]

Returns both <b>stAngleBisectors</b> of the lines.

Example: <b>AngleBisector</b>(x + y = 1, x - y = 2) yields no definite result (the reason is that any diagonal line has an infinite stAngle).

<i> In comparison, the AngleBisector(x + y = 1, x - y = 2) yields a: x = 1.5 and b: y = -0.5. </i>

<b>AngleBisector</b>(x + 3y = 0, x - 3y = 3) yields a: x = 1.5 and b: y = -0.5. 

<i> In comparison, the AngleBisector(x + 3y = 0, x - 3y = 3) yields a: x = 1.5 and b: y = -0.5. </i>

<b>AngleBisector</b>(x + 2y = 0, 3x - 4y = 0) yields a: -x + 4.8y = 0 and b: 4.8x -y = 0. 

<i> In comparison, the AngleBisector(x + 2y = 0, 3x - 4y = 0) yields a: -0.09x +y = 0 and b: x + 0.09y = 0. </i>

## stAngleBisector [ Point, Point, Point]

Returns the <b>stAngleBisector</b> of the angle defined by the three points.

Example:
<b>stAngleBisector</b>[(1, 1), (4, 4), (7, 1)] yields no definite result (the reason is that any diagonal line has an infinite stAngle).

<i> In comparison, AngleBisector((1, 1), (4, 4), (7, 1)) yields a: x = 4.</i>

<b>stAngleBisector</b>[(1, 2), (4, 4), (7, 2)] yields a: x = 4.

<i> In comparison, AngleBisector((1, 2), (4, 4), (7, 2)) yields a: x = 4.</i>

<b>stAngleBisector</b>[(-2, -1.5), (0, 0), (-2, 1)] yields a: -x + 4.8y = 0 and b: 4.8x -y = 0. 

<i> In comparison, AngleBisector((-2, -1.5), (0, 0), (-2, 1)) yields a: -0.09x +y = 0 and b: x + 0.09y = 0.</i>

Note: The second point is apex of this stAngle.




Note: See also Mode angularbisector.svg Angle Bisector tool .
