# Novos Elementos
Para levar adiante a proposta será preciso crear novos elementos ou recursos de programación. <br>
A seguinte lista irá aumentando a medida que se vaian identificando novas necesidades.

## [Obxectos](../documents/GeoGebra/Objects.md)
*  ###  Minkowskian Circles <br>
Substitúe á circunferencia euclidea (Circle) como lugar xeométrico dos puntos equidistantes dun centro dado.

Ao contrario do caso euclídeo, no que temos unha única posibilidade para cada centro (c<sub>1</sub>,c<sub>0</sub>)  e raio (R), aparecen varios posibles obxectos:
* sCircle: 
   Recolle todos os puntos cunha distancia de tipo espacial respecto do centro. <br>
   A figura corresponde a unha hipérbola equilátera cunha rama á dereita e outra á esquerda.<br>
Fórmula (co centro na orixe de coordenadas): x<sup>2</sup>-t<sup>2</sup>= R<sup>2</sup><br> 
      Para un centro distinto, a fórmula é  (x-c<sub>1</sub>)<sup>2</sup>-(t-c<sub>0</sub>)<sup>2</sup>= R<sup>2</sup><br>

* tCircle: 
   Recolle todos os puntos cunha distancia de tipo temporal respecto do centro. <br>
   A figura corresponde a unha hipérbola equilátera cunha rama superior e outra inferior.<br>
Fórmula (co centro na orixe de coordenadas): -x²+t²= R²
Para un centro distinto, a fórmula é  -(x-c<sub>1</sub>)²+(t-c<sub>0</sub>)²= R²

* stCircle: 
   Recolle todos os puntos cunha distancia de tipo temporal ou espacial respecto do centro. <br>
   A figura corresponde coa unión das dúas hipérbolas anteriores (sCircle U tCircle)<br>
Fórmula (co centro na orixe): -x<sup>2</sup>+t<sup>2</sup>= R<sup>2</sup>   U   -x<sup>2</sup>+t<sup>2</sup>= R<sup>2</sup><br>
|[MinkowskiCircles](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Interese/Images/MinkowskianCircles.png"Different Types of Minkowskian Circles")
*  ###  LightDiagonals
Este obxecto non ten correspondencia no plano euclídeo. <br>
Corresponde co lugar xeométrico dos puntos que teñen unha distancia nula respecto dun punto dado.<br>
A forma xeométrica é a dun par de rectas de pendente igual a 1 e -1 que se cortan no centro.
  
*  ###  stRegularPolygon
Consiste nunha serie de puntos situados sobre unha mesma hipérbola equilátera (stCircle) e situados uns de outros á mesma distancia (minkowskiana). Non comparte a propiedade de calquera polígono regular euclidiano de formar unha figura pechada, xa que sempre estará aberta cara ás asíntotas.

*  ###  stComplexNumber
Os números complexos minkowskianos, ainda que formalmente idénticos aos euclidianos [a+bh) frente a (a+bi), sendo tanto i como h unidades imaxinarias]  teñen propiedades alxebraicas diferentes, derivadas do feito de que h² = 1, mentres que i² = -1

*  ###  stAngle
Os ángulos na xeometría seudoeuclídea veñn determinados polo seu valor en radiáns hiperbólicos. Para comparar cos radiáns habituais, podemos considerar que no caso euclídeo o valor dun ángulo en radiáns corresponde á metade da superficie do sector circular que forma coa circunferenica unitaria. Entón, no caso sudoeuclídeo, esa definición de ángulo mantenser (substituíndo o sector curcular polo correspondente sector hiperbólico, ou stSectorCircular).

*  ###  stCircularArc
Un arco stCircular corresponde a un tramo de hipérbola (stCircle) comprendido entre dous puntos da mesma.

*  ###  stSemicircle
Se cortamos unha hipérbopla equilátera (stCircle) mediante un diámetro (liña recta que pasa polo centro da mesma) obtemos un par de seimihipérbolas (stSemiCircles).

*  ###  stCircularSector
Un sector stCircular corresponde á superficie delimitada por dous raios e o arco de hipérbola (stCircle) que os une, en estricta coprrespondencia coa definición euclídea.

*  ###  stDistance
Dados dous puntos do espazotempo  A(xA, tA) e B(xB, tB) a distancia espazotemporal entre os mesmos defínese como stD(A,B)=(xA-xB)²-(tA-tB)². Comparativamente, a distancia euclídea entre dous puntos A(xA, yA) e B(xB, yB) defínese como d(A,B)=(xA-xB)²+(yA-yB)². A distancia euclídea é sempre positiva ou nula (e neste caso, necesariamente A e B coinciden), mentres que a stDistance pode ser positiva (separación espacial), negativa (separación temporal) ou nula (separación lumínica), e neste caso non é necesario que A e B sexan coincidentes, bastando con que estean sobre unha mesma recta asintótica (de pendente unitaria).

## [Comandos](../documents/GeoGebra/Commands.md)
*  ###  stCross
*  ###  stDot
*  ###  stPerpendicularVector
*  ###  stUnitVector
*  ###  stUnitPerpendicularVector
*  ###  stReflect
*  ###  stRotate
