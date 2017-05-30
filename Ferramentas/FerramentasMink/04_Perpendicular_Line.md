# 4-Perpendicular Line
[GeoGebra manual](https://wiki.geogebra.org/en/Perpendicular_Line_Tool)

Selecting a line (or a segment) and a point creates a straight line through that point <b>stPerpendicular</b> to the line (or segment). 
    
Notes:

The line’s direction is equivalent to the <b>stPerpendicular vector</b> of the selected line or segment. 
(See also [<b>stPerpendicularVector command</b>](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Comandos/stPerpendicularVector_Command.md)).
        
This tool should have also a version applicable to <b>(2,1)D objects</b>: Select point and <b>stPerpendicular line or plane</b>.
(See also <b>[stPerpendicular Line command](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Comandos/stPerpendicularLine_Command.md)</b>).

...............................................................

### [Input & Output](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Temas/Entrada_Saida.md)

Selecting a line (or a segment) and a point creates a straight line through that point <b>stPerpendicular</b> to the line (or segment). 

### [Related Commands](https://github.com/probaxeoxebra/probaMinkoski/blob//master/Temas/ComandosRelacionados.md)

* <b>[stPerpendicular Vector](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Comandos/stPerpendicularVector_Command.md)</b>
* <b>[stPerpendicular Line](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Comandos/stPerpendicularLine_Command.md)</b>

### [Algebra](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Temas/Alxebra_Ferramentas.md)

In the Euclidean case, a Perpendicular Line to a given Line with directing vector a = (a<sub>1</sub>,a<sub>2</sub>) in the (x,y) plane through a point P (p<sub>1</sub>,p<sub>2</sub>) is obtained by making the [Cross](../Explicacions/CrossProduct.md) Product n =(a x e<sub>3</sub>), where e<sub>3</sub> is the unit vector at the orthogonal direction to the (x,y) plane: the z axis. 

![EuclideanPerpendicular](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Interese/Images/PerpendicularVector.jpg "Algebraic formulation for the Perependicular to a given Vector")

The Perpendicular Line to a Line with direction vector d(d<sub>1</sub>,d<sub>2</sub>) through a Point P (p<sub>1</sub>,p<sub>2</sub>) is the Line which passes through Point P and with direction n(d<sub>2</sub>, - d<sub>1</sub>).

<b>In the Minkowskian (1,1)D (x,t) spacetime, a stPerpendicular</b> Line to a given Line with directing vector a = (a<sub>1</sub>,a<sub>0</sub>) through a point P (p<sub>1</sub>,p<sub>0</sub>) is obtained by making the [<b>stCross</b>](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/CrossProduct.md) <b>Product n = (e<sub>2</sub> x a)</b>, where e<sub>2</sub> is the unit vector at the <b>stOrthogonal</b> direction to the <b>(x,t) plane</b>: the <b>y axis</b>.

![MinkowskianPerpendicular_1](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Interese/Images/stPerp_Calculation_1.jpg "Algebraic formulation for the stPerependicular to a given Vector")

![MinkowskianPerpendicular_2](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Interese/Images/stPerp_Calculation_2.jpg "Algebraic formulation for the stPerependicular to a given Vector")

The <b>stPerpendicular</b> to a Line with direction vector d(d<sub>1</sub>,d<sub>0</sub>) through a Point P (p<sub>1</sub>,p<sub>0</sub>) is the Line which passes through Point P and with direction n<b>(d<sub>0</sub>, d<sub>1</sub>)</b>.


### [from Euclid to Minkowski](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Temas/Euclides_Minkowski_Ferramentas.md)

A <b>stPerpendicular</b> Line to a given Line a is obtained by reflecting a about an asymptpotic line ( a line passing through the base of a and with unitary slope.

![stPerpencicular](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Interese/Images/PerpendVectors_Eucl_Mink.png "Euclidean vs. Minkowskian Perpendicularity")

### [building with available GeoGebra Tools](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Temas/ConstrucionKitBasicoGeoGebra_cadaFerramenta.md)

* [<b>GeoGebra Applet</b> for stPerpendicular Line Tool](https://sites.google.com/site/modernphysicsgeometry/geogebra_2d_sttools/4--perpendicular-line)

![Line and Point](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Ferramentas/FerramentasMink/Images/stPerpendicularLine_1.JPG "Line and Point")
![stPerpendicular Line](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Ferramentas/FerramentasMink/Images/stPerpendicularLine_2.JPG "stPerpendicular Line (in Red)")

## [Program Code](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Temas/ProgramacionFerramentas.md)

aqui viría o <b>código</b>

## [Tests](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Temas/Tests_Ferramentas.md)

aqui veñen os <b>exemplos</b> cos <b>resultados</b> agardados