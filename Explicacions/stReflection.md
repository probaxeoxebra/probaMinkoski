# stReflection

A Rotation is determined by a Line (which is built from two Points).

## Reflection about Line passing through the Origin

The Reflection of a Point P about a Line passing through the origin and a Point B can be obtained by the product of a Reflection Matrix R by the vector (column) for the point P:

b = Ra

Expressing the vectors as columns, the calculations are as follows:

* Euclidean Reflection:

![Euclidean Reflection about Origin](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/EuclidRotation_Matrix.jpg "b is the vector column for the rotation of point A about the origin and an Angle φ")

* Minkowskian stReflection:

![Minkowskian stReflection about Origin](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/MinkRotation_Matrix.jpg "b is the vector column for the stRotation (Boost) of point A about the origin and an stAngle β")

To reflect a figure, we must reflect all its generating Points.

The following figures show the Reflection of a Triangle in the Euclidean and Minkowskian cases:

![stReflection](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Images/Reflection_EuclMink.png)


## Reflection about a Line passing through Points A and B

The Reflection of a Point P about a Line passing through Points A and B can be obtained by the following expression:

b = c + R(a-c) = (I-R)c + Ra

Expressing the vectors as columns, the calculations are as follows:

* Euclidean Reflection:

![Euclidean Reflection about center C](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/EuclRotation_Matrix_Center.jpg "b is the vector column for the rotation of point A about the origin and an Angle φ")

* Minkowskian stReflection:

![Minkowskian stReflection about center C](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/MinkRotation_Matrix_Center.jpg "b is the vector column for the stRotation (Boost) of point A about the origin and an stAngle β")
