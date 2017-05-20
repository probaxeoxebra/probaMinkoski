# Novos Elementos - Atributos
Para levar adiante a proposta será preciso crear novos elementos ou recursos de programación. <br>
A seguinte lista irá aumentando a medida que se vaian identificando novas necesidades.

## [Obxectos](../documents/GeoGebra/Objects.md)
*  ###  stCircle <br>
Substitúe á circunferencia euclidea (Circle) como lugar xeométrico dos puntos equidistantes dun centro dado.

Ao contrario do caso euclídeo, no que temos unha única posibilidade para cada centro (c<sub>1</sub>,c<sub>0</sub>)  e raio (R), aparecen varios posibles obxectos, que se distinguirán entre eles polo valor dun atributo (Tipo) que pode ter os valores +1, -1 ou 0:
* stCircle con Tipo = +1: 
   Recolle todos os puntos cunha distancia de tipo espacial respecto do centro. <br>
   A figura corresponde a unha hipérbola equilátera cunha rama á dereita e outra á esquerda.<br>
Fórmula (co centro na orixe de coordenadas): x²-t²= R² <br>
      Para un centro distinto, a fórmula é  (x-c<sub>1</sub>)²-(t-c<sub>0</sub>)²= R²
      
* stCircle con con Tipo = +1: : 
   Recolle todos os puntos cunha distancia de tipo temporal respecto do centro. <br>
   A figura corresponde a unha hipérbola equilátera cunha rama superior e outra inferior.<br>
Fórmula (co centro na orixe de coordenadas): -x²+t²= R² <br>
Para un centro distinto, a fórmula é  -(x-c<sub>1</sub>)²+(t-c<sub>0</sub>)²= R²
* stCircle con Tipo = 0: 
 Este obxecto non ten correspondencia no plano euclídeo. <br> 
Corresponde co lugar xeométrico dos puntos que teñen unha distancia nula respecto dun punto dado.<br>
A forma xeométrica é a dun par de rectas de pendente igual a 1 e -1 que se cortan no centro.

A fórmula para un stCircle xeral, sería: (x-c<sub>1</sub>)²-(t-c<sub>0</sub>)²= Tipo·R²

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
Dados dous puntos do espazotempo  A(xA, tA) e B(xB, tB) a distancia espazotemporal entre os mesmos defínese como stD(A,B)²=(xA-xB)²-(tA-tB)². Comparativamente, a distancia euclídea entre dous puntos A(xA, yA) e B(xB, yB) defínese como d(A,B)²=(xA-xB)²+(yA-yB)². O cadrado d distancia euclídea é sempre positivo ou nulo (e neste caso, necesariamente A e B coinciden), mentres que o cadrado da stDistance pode ser positivo (separación espacial), negativo (separación temporal) ou nulo (separación lumínica), e neste caso non é necesario que A e B sexan coincidentes, bastando con que estean sobre unha mesma recta asintótica (de pendente unitaria).

## [Comandos](../documents/GeoGebra/Commands.md)
*  ###  stCross
*  ###  stDot
*  ###  stPerpendicularVector
*  ###  stUnitVector
*  ###  stUnitPerpendicularVector
*  ###  stReflect
*  ###  stRotate
