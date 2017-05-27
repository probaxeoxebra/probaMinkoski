[at GeoGebra Manual](https://wiki.geogebra.org/en/PerpendicularVector_Command)

## stPerpendicularVector[ <Line> ]

    Returns the stPerpendicular vector of the line.
    Example:
    
    Let Line[ (1, 4), (5, -3) ] be the line j. stPerpendicularVector[ j ] yields the stPerpendicular vector u=(-7, 4) of the line j.

    Note: A line with equation ax + bt = c has the stPerpendicular vector (a, -b).

## stPerpendicularVector[ <Segment> ]

    Returns the stPerpendicular vector of the segment with the same stLength.
    Example:
    
    Let Segment[ (3, 2), (14, 5) ] be the segment k. stPerpendicularVector[ k ] yields the perpendicular vector u=(3, 11) of the segment k.

## stPerpendicularVector[ <Vector> ]

    Returns the stPerpendicular vector of the given vector.
    Example:
    
    Let Vector[ (-12, 8) ] be the vector u. stPerpendicularVector[ u ] yields the stPerpendicular vector v=(8, -12) of the vector u.

    Note: In the Menu view cas.svg CAS View undefined variables should allowed as well.

        Example: stPerpendicularVector[(a, b)] should yield the vector {b, a}.

stPerpendicularVector[ <Plane> ]

    Creates a vector stOrthogonal to the plane.
    Examples:
    
    stPerpendicularVector[ xOyPlane ] yields the stPerpendicular vector u=(0, 0, 1) of the xOy plane.
    
    stPerpendicularVector[ xOtPlane ] yields the stPerpendicular vector u=(0, 1, 0) of the xOt plane.
