# Novos Elementos
Para levar adiante a proposta será preciso crear novos elementos ou recursos de programación. <br>
A seguinte lista irá aumentando a medida que se vaian identificando novas necesidades.

## Obxectos
  ###  stCircle <br>
Substitúe á circunferencia euclidea (Circle) como lugar xeométrico dos puntos equidistantes dun centro dado.

Ao contrario do caso euclídeo, no que temos unha única posibilidade para cada centro (c<sub>1</sub>,c<sub>0</sub>)  e raio (R), aparecen varios posibles obxectos:
* sCircle: 
   Recolle todos os puntos cunha distancia de tipo espacial respecto do centro. <br>
   A figura corresponde a unha hipérbola equilátera cunha rama á dereita e outra á esquerda.<br>
Fórmula (co centro na orixe de coordenadas): x<sup>2</sup>-t<sup>2</sup>= R<sup>2</sup><br> 
      Para un centro distinto, a fórmula é  (x-c<sub>1</sub>)<sup>2</sup>-(t-c<sub>0</sub>)<sup>2</sup>= R<sup>2</sup><br>. 

* tCircle: 
   Recolle todos os puntos cunha distancia de tipo temporal respecto do centro. <br>
   A figura corresponde a unha hipérbola equilátera cunha rama superior e outra inferior.<br>
Fórmula (co centro na orixe de coordenadas): -x<sup>2</sup>+t<sup>2</sup>= R<sup>2</sup><br>
Para un centro distinto, a fórmula é  -(x-c<sub>1</sub>)<sup>2</sup>+(t-c<sub>0</sub>)<sup>2</sup>= R<sup>2</sup><br> 

* stCircle: 
   Recolle todos os puntos cunha distancia de tipo temporal ou espacial respecto do centro. <br>
   A figura corresponde coa unión das dúas hipérbolas anteriores (sCircle U tCircle)<br>
Fórmula (co centro na orixe): -x<sup>2</sup>+t<sup>2</sup>= R<sup>2</sup>   U   -x<sup>2</sup>+t<sup>2</sup>= R<sup>2</sup><br>


   ###  LightDiagonals
Este obxecto non ten correspondencia no plano euclídeo. <br>
Corresponde co lugar xeométrico dos puntos que teñen unha distancia nula respecto dun punto dado.<br>
A forma xeométrica é a dun par de rectas de pendente igual a 1 e -1 que se cortan no centro.
  
   ###  stRegularPolygon
   ###  stComplexNumber
   ###  stAngle
   ###  stCircularArc
   ###  stSemicircle
   ###  stCircularSector
   ###  stDistance

## Comandos
   ###  stCross
   ###  stOrthogonal
   ###  stReflect
   ###  stRotate
