# Introdución ao espazotempo de Minkowski

## O espazotempo e Minkowski é o que sustenta a teora da relatividade e, en xeral, toda a física.
Minkowski explicou que había tres dimensións espaciais (que corresponden coas do espazo de Euclides) e unha dimensión adicional correspondente ao tempo.

Temos deste xeito un espazotempo tetradimensional, de coordenadas (x, y, z, t). 

As distancias neste espazotempo defínense pola seguinte métrica:

  d² =  x² + y² + z² - t²

Para encaixar coa presentación de GeoGebra, facemos unha primeira redución dimensional (prescindindo da dirección "z") para quedarnos con dúas dimensións espaciais e unha temporal, deste xeito:
* x (ancho)
* y (fondo)
* t (alto)

## Plano de Minkowski
Podemos proxectar este espazotempo tridimensional de Minkowski  (x, y, t) sobre un plano eliminando unha das dimensións espaciais (por exemplo, o eixe "y") 

Obtemos deste xeito un plano (x,t) coa métrica do espazotempo de Minkowski orixinal. 

  d² = x² - t²

Esta é a estrurura alxebraica sobre o que se sustentaría o entorno de xeometría dinámica que presentamos nesta proposta para Geogebra.
![(2,2D e (2,1)D](https://github.com/probaxeoxebra/probaMinkoski/blob/master/IMAGES/11D-21D%20views.jpg "espazotempo esquerda: (1,1)D e dereita: (2,1)D ")

# CONVENIOS:
O paso das formulacións alxegraicas dende o espazo eucídeo ao espazotempo de Minkowski pódese facer de varios xeitos,
estando as diferencias baseadas na elección da coordenadas con signatura negativa e na orde na que se colocan os índices e se definen os produtos vectoriais (Cross e Perpendicular).

Nesta proposta, seguimos os seguintes convenios:

* A coordanada de signatura negativa é a TEMPORAL (  d² = x² - t²). 
Deste xeito, mantéñense as coordenadas espaciais inalteradas)
* Para usar a definición do produto stCross como a x b = -I (a ^b), 
definimos I = e<sub>1</sub> e<sub>0</sub> e<sub>2</sub>  
(deste xeito, conseguimos que a relación entre o [Cross euclideo e o stCross de Minkowski sexa unha inversión da coordenada temporal](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Explicacions/CrossProduct.md), o cal é máis visual (sobre todo, para tres dimensions) que invertir todas as coordenadas espacias.
* Para establecer o vector stPerpendicular a un stVector v no plano (x,t), 
usamos stPerp[v]= stCross (e<sub>2</sub> , v). Deste xeito, 
conseguimos que dous vectores [stPerpendiculares](https://github.com/probaxeoxebra/probaMinkoski/blob/master/Ferramentas/FerramentasMink/4_Perpendicular_Line.md) simplemente intercambien as coordenadas espacial e temporal.
