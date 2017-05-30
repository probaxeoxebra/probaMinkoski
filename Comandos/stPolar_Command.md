# stPolar Command

[<b>Polar Command</b> at GeoGebra Manual](https://wiki.geogebra.org/en/Polar_Command)

  <i> The Polar Command in GeoGebra applies to any kind of conic section, but we restrict the application of the <b>stPolar</b> Command initially to <b>stCircles</b>  </i>
  
   [Polar Line to a Circle, in Wikipedia (Spanish)](https://es.wikipedia.org/wiki/Recta_polar)
   
   [Polar Line to a Conic section, in Wikipedia (English)](https://en.wikipedia.org/wiki/Pole_and_polar)
   
   
## stPolar[ Point, stCircle ]
 Creates the <b>stPolar</b> line of the given point relative to the <b>stCircle</b>. 
 
  Example: 
  
 <b>stPolar</b>[(3,4), (x-2)²-(t-1)² = - 4] creates the line  t - 3x = 5
  
  <i> in the euclidean case, <b>stPolar</b>[(3,4), (x-2)² + (y-1)² = - 4] creates the line  x + 3y = 9  </i>

Note: See also  <b>stPolar or Diameter Line tool</b>.

The previous test cases can be seen together in the next Figure:
* Polar Line of Point (3,4) for the Circle of Radius 2 centered in (2,1) (both in black) and 
* <b>stPolar Line</b> of Point (3,4) for the <b>stCircle</b> of Radius 2 centered in (2,1)  (both in Red color)

 ![stPolarLine_2](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Comandos/Images/stPolarLine_Test2.JPG)

and reverse of the previous :

## stPolar[Line, stCircle]

 Example: 
 
 <b>stPolar</b>[ t - 3x = 5 , (x-2)²-(t-1)² = - 4] creates the point (3, 4)
    
  <i> Again in the euclidean case, Polar[ x + 3y = 9 , (x-2)² + (y-1)² = - 4] creates the point (3, 4)</i>    
    

    
    
  
 
