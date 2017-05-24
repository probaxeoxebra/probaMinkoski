# stRotation

A Rotation is determined by a Point (center) and an Angle.

## Rotation about the Origin

The Rotation of a Point A about the origin can be obtained by the product of a Rotation Matrix R by the vector (column) for the point A:

b = Ra

Expressing the vectors as columns, this expression is as follows (when the center is at the origin):

* Euclidean Rotation:

![Euclidean Rotation about Origin](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/EuclidRotation_Matrix.jpg "b is the vector column for the rotation of point A about the origin and an Angle φ")

* Minkowskian stRotation (Boost):

![Minkowskian stRotation about Origin](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/MinkRotation_Matrix.jpg "b is the vector column for the stRotation (Boost) of point A about the origin and an stAngle β")

To rotate a figure, we must rotate all its generating Points.

The following figures show the Rotation of a Triangle in the Euclidean and Minkowskian cases:

![stRotation](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Images/Rotation_EuclMink.png)


## Rotation about a center C

The Rotation of a Point A about a center C can be obtained by the following expression:

b = c + R(a-c) = (I-R)c + Ra

Expressing the vectors as columns, this expression is as follows:

* Euclidean Rotation:

![Euclidean Rotation about center C](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/EuclRotation_Matrix_Center.jpg "b is the vector column for the rotation of point A about the origin and an Angle φ")

* Minkowskian stRotation (Boost):

![Minkowskian stRotation about center C](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/MinkRotation_Matrix_Center.jpg "b is the vector column for the stRotation (Boost) of point A about the origin and an stAngle β")


