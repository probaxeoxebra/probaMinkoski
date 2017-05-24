# stReflection

A Reflection is determined by a Line (which is built from two Points).

## Reflection about Line passing through the Origin

The Reflection of a Point P about a Line passing through the origin and a Point B can be obtained by the product of a Reflection Matrix R by the vector (column) for the point P:

b = Ra

Expressing the vectors as columns, the calculations are as follows:

* Euclidean Reflection:

![Euclidean Reflection about Origin](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/EuclidReflect_Origin.jpg "q is the vector column for the reflection of point P about a Line passing through the origin")


![EuclideanReflection_Matrix](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Images/EuclReflect_Matrix.JPG "Matrix elements(columns): Blue Vector(1), Red Vector(2)")

* Minkowskian stReflection:
  * About spacelike Reflecting Line (stType = +1)

![Minkowskian stReflection about Origin_s](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/MinkReflect_Origin_s.jpg "q is the vector column for the stReflection of point P about a spacelike Line passing through the origin")

  * About timelike Reflecting Line (stType = -1)
  
![Minkowskian stReflection about Origin_t](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/MinkReflect_Origin_t.jpg "q is the vector column for the stReflection of point P about a timelike Line passing through the origin")

Both cases can be unified by introducing the stType into the expression:

b = (stType)Ra

(bearing in mind that the Matrix for the timelike reflecting direction is the opposite of the corresponding spacelike Matgrix)

![MimkowskianReflection_SpacelikeMatrix](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Images/MinkReflect_sMatrix.JPG "Matrix elements(columns): Blue Vector(1), Red Vector(2)")
![MimkowskianReflection_TimelikeMatrix](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Images/MinkReflect_tMatrix.JPG "Matrix elements(columns): Blue Vector(1), Red Vector(2)")

To reflect a figure, we must reflect all its generating Points.

The following figures show the Reflection of a Point in the Euclidean and Minkowskian cases:
![stReflection](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Images/Reflection_EuclMink.png)

## Reflection about a Line passing through Points A and B

The Reflection of a Point P about a Line passing through Points A and B can be obtained by the following expression:

b = c + R(a-c) = (I-R)c + Ra

Expressing the vectors as columns, the calculations are as follows:

* Euclidean Reflection:

![Euclidean Reflection about center C](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/EuclidReflect_PointA.jpg "q is the vector column for the reflection of point P about a Line passing through Points A and B")

* Minkowskian stReflection:

  * About spacelike Reflecting Line (stType = +1)
  
![Minkowskian stReflection about PointA_s](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/MinkReflect_PointA_s.jpg "q is the vector column for the stReflection of point P about a spacelike Line passing through Points A and B")

  * About timelike Reflecting Line (stType = -1)
  
![Minkowskian stReflection about PointA_t](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/Formulas/MinkReflect_PointA_t.jpg "q is the vector column for the stReflection of point P about a timelike Line passing through Points A and B")

