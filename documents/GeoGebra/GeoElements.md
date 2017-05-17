GeoGebra works with appropriate Java classes for ​such elements which are called ​GeoElements. 

The following figure shows the various Java classes for different kinds of geometrical objects.


To work on such objects we define ​algorithms. 

For example, a line can be defined with the points lying on it. 

As inputs of ​GeoPoint A and GeoPoint B we can obtain an output of ​GeoLine g by calling the Java method ​AlgoJoinPoints (see figure below).

GeoGebra must take care of the hierarchy of the dependent objects. 

That means that each time the user drags point A or point B, the line g must also be redisplayed after recalculating its geometrical properties.
