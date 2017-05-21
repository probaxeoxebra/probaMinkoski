# Novos Elementos
Para levar adiante a proposta será preciso crear novos elementos ou recursos de programación. <br>
A seguinte lista irá aumentando a medida que se vaian identificando novas necesidades.

## [Obxectos](../documents/GeoGebra/Objects.md)
*  ###  stDistance
Dados dous puntos do espazotempo  A(xA, tA) e B(xB, tB) a distancia espazotemporal entre os mesmos defínese como d(A,B)²=(xA-xB)²-(tA-tB)². Comparativamente, a distancia euclídea entre dous puntos A(xA, yA) e B(xB, yB) defínese como d(A,B)²=(xA-xB)²+(yA-yB)². O cadrado da distancia euclídea é sempre positivo ou nulo (e neste caso, necesariamente A e B coinciden), mentres que o cadrado da distancia seudoeuclídea pode ser positivo (separación espacial), negativo (separación temporal) ou nulo (separación lumínica), e neste caso non é necesario que A e B sexan coincidentes, bastando con que estean sobre unha mesma recta asintótica (de pendente unitaria).
#### stType
Para definir unha stDistance sen precisar de números complexos, podemos acudir ao atributo stType, que definiremos como stType = d²/|d²| cando d² non é nulo (neste caso, stType pode adoptar os valores +1 ou -1), e como stType = 0 cando d²=0.

Podemos definir agora a stDistance como stDistance = stType·|sqrt(|d²|)|
* Para intervalos de tipo espacial, stDistance é positiva
* Para intervalos de tipo temporal, stDistance é negativa
* Para intervalos de tipo lumínico, stDistance é nula
![stDistances](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Interese/Images/stDistance.png "Spatial Distance (stType = +1), Timelike Distance (stType = -1) and Lightlike Distance (stType = 0)")
*  ###  stCircle <br>
Substitúe á circunferencia euclidea (Circle) como lugar xeométrico dos puntos equidistantes dun centro dado.

Ao contrario do caso euclídeo, no que temos unha única posibilidade para cada centro (c<sub>1</sub>,c<sub>0</sub>)  e raio (R), aparecen varios posibles obxectos, que se distinguirán entre eles polo valor do atributo (stType) que (como vimos antes)  pode ter os valores +1, -1 ou 0:
* stCircle con stType = +1: 
   Recolle todos os puntos cunha distancia de tipo espacial respecto do centro. <br>
   A figura corresponde a unha hipérbola equilátera cunha rama á dereita e outra á esquerda.<br>
Fórmula (co centro na orixe de coordenadas): x²-t²= R² <br>
      Para un centro distinto, a fórmula é  (x-c<sub>1</sub>)²-(t-c<sub>0</sub>)²= R²
      
* stCircle con stType = +1: : 
   Recolle todos os puntos cunha distancia de tipo temporal respecto do centro. <br>
   A figura corresponde a unha hipérbola equilátera cunha rama superior e outra inferior.<br>
Fórmula (co centro na orixe de coordenadas): -x²+t²= R² <br>
Para un centro distinto, a fórmula é  -(x-c<sub>1</sub>)²+(t-c<sub>0</sub>)²= R²
* stCircle con stType = 0: 
 Este obxecto non ten correspondencia no plano euclídeo. <br> 
Corresponde co lugar xeométrico dos puntos que teñen unha distancia nula respecto dun punto dado.<br>
A forma xeométrica é a dun par de rectas de pendente igual a 1 e -1 que se cortan no centro.

A fórmula para un stCircle xeral, sería: (x-c<sub>1</sub>)²-(t-c<sub>0</sub>)²= stType·R²

![stCircles_stType](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Interese/Images/stCircles_stType.png "stCircles with different stType")

*  ###  stComplexNumber
Os números complexos minkowskianos, ainda que formalmente idénticos aos euclidianos [a+bh) frente a (a+bi), sendo tanto i como h unidades imaxinarias]  teñen propiedades alxebraicas diferentes, derivadas do feito de que h² = 1, mentres que i² = -1

*  ###  stAngle
Os ángulos na xeometría seudoeuclídea veñen determinados polo seu valor en radiáns hiperbólicos. Para comparar cos radiáns habituais, podemos ter en conta que, no caso euclídeo, o valor dun ángulo en radiáns corresponde ao doble da superficie do sector circular que forma coa circunferenica unitaria. Entón, no caso seudoeuclídeo, esa definición de ángulo mantense (substituíndo o sector circular polo correspondente sector hiperbólico, ou stSectorCircular).
![Angle_Eucl_Mink](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Interese/Images/Angle_Eucl_Mink.png "Left:Euclidean Angle, Right stAngle (Minkowskian. In both cases: Double of sector area (A)")
*  ###  stCircularArc
Un arco stCircular corresponde a un tramo de hipérbola (stCircle) comprendido entre dous puntos da mesma.

*  ###  stSemicircle
Se cortamos unha hipérbola equilátera (stCircle) mediante un diámetro (liña recta que pasa polo centro da mesma) obtemos un par de seimihipérbolas (stSemiCircles).

*  ###  stCircularSector
Un sector stCircular corresponde á superficie delimitada por dous raios e o arco de hipérbola (stCircle) que os une, en estricta coprrespondencia coa definición euclídea.

![stCircleElements](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Interese/Images/CircleElements.png "Left: Euclidean Circle Elements, Right: Minkowskian stCircle Elements")


## [Comandos](../documents/GeoGebra/Commands.md)
*  ###  [stCross](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/CrossProduct.md)
*  ###  [stDot](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/DotProduct.md)
*  ###  [stPerpendicularVector](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/stPerpendicularVector.md)
*  ###  stUnitVector
*  ###  stUnitPerpendicularVector
*  ###  stReflect
*  ###  stRotate
