# stIncircle Command

[<b>Incircle Command</b> at GeoGebra Manual](https://wiki.geogebra.org/en/Incircle%20Command)

<i> Note: an stIncircle is a stCircle ( equilateral and straight Hyperbola) 
which is tangent to the three sides of the triangle (or to its containing straight lines)</i>

### stIncircle[ Point, Point, Point ]
    Returns stIncircle of the triangle formed by the three Points.
    Example: Let O=(0, 0), A=(3, 0) and B=(0, 5) be three points: Incircle[O, A, B] yields (x - 1.08)² + (y - 1.08)² = 1.18 in Menu view algebra.svg Algebra View and draws the corresponding circle in Menu view graphics.svg Graphics View.

## Comments
There are three possible types of stCircles which differ inthe value of their stType:
* stType = +1 for spacelike radii (hyperbola with left and right arms)
* stType = -1 for timelike radii (hyperbola with upper and lower arms)
* stType = 0 (degenerated case, consisting in tho diagonal lines
