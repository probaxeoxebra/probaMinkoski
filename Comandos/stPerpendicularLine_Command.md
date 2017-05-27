[at GeoGebra Manual](https://wiki.geogebra.org/en/PerpendicularLine_Command)

# stPerpendicularLine[ Point, Line ]

Creates a line through the point <b>stPerpendicular</b> to the given line.
    Example:
Let c: -3x + 4y = -6 be a line and A = (-2, -3) a point. <b>stPerpendicularLine[ A, c ]</b> yields the line d: <b>4x - 3y = 1</b>.

Note: For (2,1)D objects a third argument is added to this command to specify the behavior: if 2D view is active, plane z=0 is used as third argument, if 3D view is active, space is used instead. See <b>stPerpendicularLine[ Point, Line, Context ]</b> further below for details.
# stPerpendicularLine[ Point, Segment ]
Creates a line through the point <b>stPerpendicular</b> to the given segment.
    Example:
Let c be the segment between the two points A = (-3, 3) and B = (0, 1). <b>stPerpendicularLine[ A, c ]</b> yields the line d: <b>3x + 2y = - 3</b>.

# stPerpendicularLine[ Point, Vector ]
Creates a line through the point <b>stPerpendicular</b> to the given vector.
    Example:
Let u = Vector[ (5, 3), (1, 1) ] and A = (-2, 0) a point. <b>stPerpendicularLine[ A, u ]</b> yields the line c: 2x + y = -4.


# stPerpendicularLine[ Point, Plane ]

Creates a <b>stPerpendicular</b> line to the plane through the given point. 

# stPerpendicularLine[ Line , Line ]

Creates a <b>stPerpendicular</b> line to the given lines through the intersection point of the two lines. 
    
# stPerpendicularLine[ Point, Direction, Direction ]

Creates a <b>stPerpendicular</b> line to the given directions (that can be lines or vectors) through the given point. 

# stPerpendicularLine[ Point, Line, Context ]

Creates a <b>stPerpendicular</b> line to the line through the point and depending on the context.

## * stPerpendicularLine[ Point, Line, Plane ] 

creates a <b>stPerpendicular</b> line to the given line through the point and parallel to the plane.
## * stPerpendicularLine[ Point, Line, space ] 

creates a <b>stPerpendicular</b> line to the given line through the point. The two lines have an intersection point. This command yields undefined if the point is on the line in 3D.
