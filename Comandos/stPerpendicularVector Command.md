[at GeoGebra Manual](https://wiki.geogebra.org/en/PerpendicularVector_Command)

## stPerpendicularVector[ Line ]

 Returns the <b>stPerpendicular vector</b> of the line.
 Example:
    
 Let Line[ (1, 4), (5, -3) ] be the line j. <b>stPerpendicularVector[ j ]</b> yields the <b>stPerpendicular vector u=(-7, 4)</b> of the line j.

Note: A line with equation ax + bt = c has the <b>stPerpendicular vector (a, -b)</b>.

## stPerpendicularVector[ Segment ]

Returns the <b>stPerpendicular vector</b> of the segment with the same <b>stLength</b>.
    Example:
    
Let Segment[ (3, 2), (14, 5) ] be the segment k. <b>stPerpendicularVector[ k ]</b> yields the <b>stPerpendicular vector u=(3, 11)</b> of the segment k.

## stPerpendicularVector[ Vector ]

Returns the <b>stPerpendicular vector</b> of the given vector.
    Example:
    
Let Vector[ (-12, 8) ] be the vector u. <b>stPerpendicularVector[ u ]</b> yields the <b>stPerpendicular vector v=(8, -12)</b> of the vector u.

Note: In the Menu view cas.svg CAS View undefined variables should allowed as well.

  Example: <b>stPerpendicularVector[(a, b)]</b> should yield the vector <b>{b, a}</b>.

stPerpendicularVector[ Plane ]

 Creates a vector <b>stOrthogonal</b> to the plane.
    Examples:
    
 <b>stPerpendicularVector[ xOyPlane ]</b> yields the <b>stPerpendicular vector</b> u=(0, 0, 1) of the xOy plane.
    
 <b>stPerpendicularVector[ xOtPlane ]</b> yields the <b>stPerpendicular vector</b> u=(0, 1, 0) of the xOt plane.
