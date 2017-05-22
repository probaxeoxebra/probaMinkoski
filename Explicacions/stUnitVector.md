# Unit stVector

A Unit stVector from a point on a given direction is obtained by creating a unit stCircle centered at the base point and drawing a Vector from the center to the intersection with the Vector direction.
![stUnitPerpencicular](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Images/UnitVectors_EuclMink.png "Euclidean vs. Minkowskian Unit Perpendicularity")

To obtain the unit vector for a given direction (Line) we must first identify two points (A,B) on the line.

We will call V the vector stretching from A to B.

The unit vector is then obtained by dividing the vector V by its modulus |V|.

This last step is different for the Euclidean and Minkowskian cases, because of the way the modulus is calculated in both cases.

Euclidean Modulus: |V| = |(V<sub>1</sub>,V<sub>2</sub>,V<sub>3</sub>)| = sqrt(V<sub>1</sub>² + V<sub>2</sub>² + V<sub>3</sub>² )

Minkowskian Modulus: |V| = |(V<sub>1</sub>,V<sub>2</sub>,V<sub>0</sub>)| = sqrt[abs(V<sub>1</sub>² + V<sub>2</sub>² - V<sub>0</sub>²)]

In the special case where the minkowskian modulus is zero, the Unit stVector does not exist.
