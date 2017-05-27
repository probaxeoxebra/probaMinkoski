# 4-Perpendicular Line
[GeoGebra manual](https://wiki.geogebra.org/en/Perpendicular_Line_Tool)

Selecting a line (or a segment) and a point creates a straight line through that point <b>stPerpendicular</b> to the line (or segment). 
    
Notes:

The line’s direction is equivalent to the <b>stPerpendicular vector</b> of the selected line or segment. (See also <b>stPerpendicularVector command</b>).
        
This tool should have also a version applicable to <b>(2,1)D objects</b>: Select point and <b>stPerpendicular line or plane</b>.
        
See also <b>stPerpendicularLine command</b>. 

...............................................................

### [Input & Output](../master/Temas/Entrada_Saida.md)

Selecting a line (or a segment) and a point creates a straight line through that point <b>stPerpendicular</b> to the line (or segment). 
In the Euclidean case, a Perpendicular Line to a given Line with directing vector v = (v<sub>1</sub>,v<sub>2</sub>) in the (x,y) plane through a point A (a<sub>1</sub>,a<sub>2</sub>) is obtained by making the [Cross](../Explicacions/CrossProduct.md) Product w =(v x e3), where e<sub>3</sub> is the unit vector at the orthogonal direction to the (x,y) plane: the z axis. Tle Perpendicular is the Line which passes through Point A and with direction w.

![EuclideanPerpendicular](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Interese/Images/PerpendicularVector.jpg "Algebraic formulation for the Perependicular to a given Vector")

In the same way, but now in the Minkowskian (1,1)D (x,t) spacetime, a <b>stPerpendicular</b> Line to a given Line with directing vector v = (v<sub>1</sub>,v<sub>2</sub>) in the (x,y) plane through a point A (a<sub>1</sub>,a<sub>2</sub>) is obtained by making the [stCross](../Explicacions/CrossProduct.md) Product w = (v x e<sub>2</sub>), where e<sub>2</sub> is the unit vector at the orthogonal direction to the (x,t) plane: the y axis.

![MinkowskianPerpendicular](../Interese/Images/stPerpendicularVector.jpg "Algebraic formulation for the stPerependicular to a given Vector")

### [Related Commands](../Temas/ComandosRelacionados.md)

<b>stPerpendicular Vector</b>,  <b>stPerpendicular Line</b>

### [Algebra](../Temas/Alxebra_Ferramentas.md)



### [from Euclid to Minkowski](../Temas/Euclides_Minkowski_Ferramentas.md)

A <b>stPerpendicular</b> Line to a given Line a is obtained by reflecting a about an asymptpotic line ( a line passing through the base of a and with unitary slope.

![stPerpencicular](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Interese/Images/PerpendVectors_Eucl_Mink.png "Euclidean vs. Minkowskian Perpendicularity")

[Perpendicularidade de Euclides e de <b>Minkowski</b>](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/stPerpendicularVector.md)

### [building with available GeoGebra Tools](../Temas/ConstrucionKitBasicoGeoGebra_cadaFerramenta.md)

aqui ven o enlace a un <b>applet de GeoGebra</b>

## [Program Code](../Temas/ProgramacionFerramentas.md)

aqui viría o <b>código</b>

## [Tests](../Temas/Tests_Ferramentas.md)

aqui veñen os <b>exemplos</b> cos <b>resultados</b> agardados
