# Estrutura

A proposta estrutúrase do seguinte xeito:

Comezamos por presentar as particularidades matemáticas e xeométricas do plano de Minkowski fronte ao plano euclideo habitual.<br>
Deste xeito, identifícanse mellor os elementos que debemos modificar e o resultado agardado destas modificacións.

Á luz do anterior, faise a proposta de desenvolvemento dunha estrutura de programación que permita usar as posibilidades do entorno de xeometría dinámica de GeoGebra no marco do plano sudoeclídeo de Minkowski.<br> 
Para elo, identifícanse os novos obxectos, procedementos e comandos que sera preciso engadir aos xa existentes para utilizalos nas ferramentas xeométricas.

Continuamos pola análise en detalle das ferramentas de GeoGebra na versión 2D online, identificando tres tipos entre as 66 ferramentas dusponibles:
* 32 ferramentas que non deberían modificarse para nada
* 11 ferramentas nas que debería engadirse un (ou varios obxectos) propios do novo entorno seudoeuclideo (por exemplo: stCircle, stArc, stRegularPolygon) de xeito que a ferramenta poida traballar con eles do mesmo xeito que o fai cos que xa ten asignados.
* 23 ferramentas que deberan ser modificadas na súa estrurura ou procesos internos. Ainda que as modificacións non deberían ser moi significativas (na maiora dos casos, implican identificar novos obxectos e modificar algún(s) signoas nos procesos matemáticos), é preciso ter unha perspectiva clara do fluxo de información en cada ferramenta para evitar problemas de execución.

Para cada ferramenta, a análise faise contemplando diversos temas, dun xeito paralelo para todas elas.<br> 

* Entrada e Saída
* Álxebra
* de Euclides a Minkowski
* construción co kit básico (euclídeo)  de GeoGebra
* Tests

Estes temas agrúpanse tamén nouto apartado, para poder facer un comparativo directo entre todas as ferramentas nun determinado aspecto.

Finalmente, preséntanse unha serie de consideracións respecto ao interese de realizar este proxecto e as posibilidades de desenvolvemento futuro, coa intención de despertar o interese nos programadores capacitados para realizar a tarefa proposta.

