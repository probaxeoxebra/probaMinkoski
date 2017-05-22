# stAngles 

## Euclidean 2D plane 

We can associate an Angle to every vector in the following way:  Vector:   v = (v1, v2)   →    Angle: φ = atan (v2/v1)

The unit vector for this direction can then be written as  u = (cos φ , sin φ)

## Minkowskian (1,1)D plane 

We can also associate an stAngle to every vector in an analogous way:  

Vector:   v = (v1, v0)   →    stAngle:   φ = atanh [ (v0/v1) <sup>stType</sup>  ]

where  atanh is the inverse hyperbolic tangent function, and   using  v2  = v12 -v02  

 if  v2 = 0   →   stType = 0   ,  otherwise   stType = v2 / abs(v2 )
 
The resulting values for stType are: 
* stTipe = +1 for spacelike vectors  (v1  >  v0)  
* stTipe = +1 for timelike vectors  (v1  <  v0) 
* stTipe = 0 for lightlike vectors  (v1  =  v0)    

The stUnitVector in the minkowskian case can be written as 

* u = (cosh φ , sinh φ)  for spacelike vectors (stType = +1)

* u = (sinh φ , cosh φ)  for timelike vectors (stType =  -1)

* u is nonexistent for lightlike vectors (stType = 0)


# Geometric interpretation of Angles as Areas

## Euclidean Plane
* The Angle (in rads) is the measure of the Arc Length of a Unit Circle.
* The Angle is also the double of the Area enclosed by a Unit Circle Sector.

For example, the Angle of a whole circle is 2π, which is the length of its unit circumference, 2π·r,  and two times the area of the unit circle: A = π·r2  (r = 1)


## Minkowski Spacetime
* The stAngle is the measure of the Arc stLength of a Unit stCircle.
* The stAngle is also the double of the Area enclosed by a Unit stCircle Sector.

![stAngle as Area](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Images/Angle_asArea.JPG "Visual explanation for the equivalence between stAngle and stSector Area")

In the figure, point P(x,t) on a Unit stCircle (left) marks a stCircular Sector (red) whose Area is A. 

Rotating the figure 45º , the equation of the stCircle, in the new coordinates (r,l) , is: r·l = ½ .

It is easy to check at the right figures that the area of both green triangles has the same value (T = r·l/2 = ¼ ). 

The Area A, thus, is equal to the integral of the hyperbolic curve between the values 1/√2 and r.  

Integrating the equation l = ½ r<sup>-1</sup>  yields  A =∫ldr = ½  ∫r<sup>-1</sup> dr = ½ ln r

Between 1/√2 and r, we get A = ½ [ln r - ln(1/√2)] = ½ ln (r√2) .

Applying φ = 2A, we have   φ = ln (r√2) 

Getting back to the original coordinates, r = 1/√2 (x+y), so  φ = ln (x+y) 

To see that this is in accordance with the usual definition, we transform this expression to get x+t = e<sup>φ</sup>   

Recalling that x = sinh φ = ½ (e<sup>φ</sup>  - e<sup>-φ</sup>  )  and 

t = cosh φ = ½ (e<sup>φ</sup>  + e<sup>-φ</sup>  )  

x + t =  sinh φ  +  cosh φ =  e<sup>φ</sup>  
