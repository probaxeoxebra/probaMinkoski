# stCross Command

[<b>Cross Command</b> at GeoGebra Manual](https://wiki.geogebra.org/en/Cross_Command)

### stCross[ stVector u , stVector v ]

Calculates the <b>stCross product</b> of u and v. Instead of vectors you can also use lists.
    Example:
    
<b>stCross</b>[(1, 3, 2), (0, 3, -2)] yields <b>(-12, 2, - 3)</b>, 

<b>stCross</b>[{1, 3, 2}, {0, 3, -2}] yields <b>{-12, 2, - 3}</b>

<i> Note: The result is nearly the same as in the Euclidean Cross, the only change being a minus sign in the time-coordinate</i>

For <b>(1,1)D spacetime</b> vectors or points the result is the <b>y-coordinate</b> of the actual <b>stCross product</b>.

   Example: <b>stCross/</b>[(1,2),(4,5)] yields -3.
    
<i> Note: In this case, the result is the same as in the Euclidean Cross, 
but changing the euclidean z-coordinate by the minkowskian <b>y-coordinate</b>. </i>
    
Note Hint: If a vector in the Menu view cas.svg CAS View contains undefined variables, 
the command yields a formula for the <b>stCross</b> product, e.g. 

<b>stCross[(a, b, c), (d, e, f)] yields (b f - c e, -a f + c d, - a e + b d).</b>

<i> Note: The result is again nearly the same as in the Euclidean Cross, the only change being a minus sign in the time-coordinate</i>

The geometrical meaning of this change in sign of the time-coordinate is a reflection about the spatial plane.

See also [CrossProduct: Euclid vs. Minkowski](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/CrossProduct.md)
