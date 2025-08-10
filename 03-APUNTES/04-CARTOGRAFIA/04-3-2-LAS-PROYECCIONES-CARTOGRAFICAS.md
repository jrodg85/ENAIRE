
# 3.2 Las proyeccines cartográficas.

## 3.2.1 Concepto.

Se entiende por sistema de representación o proyección cartográfica a las trasformaciones matemáticas que permiten representar o proyectar la Tierra en un plano.

![[195-EJEMPLO-PROYECCION-CARTOGRAFICA.jpg]]

Dado que no existe la posibilidad geométrica y/o analítica de transformar un área esférica en una plana sin deformarla, cualquier mapa generado a partir de una proyección cartográfica, llevará implícitas una serie de distorsiones respecto a la superficie real que representa, que tienen que ver con las distancias entre puntos, los ángulos entre líneas o curvas, y la equivalencia entre áreas.

Por este motivo, las proyecciones cartográficas no sólo estudian la forma de reproducir la superficie terrestre, sino que también intentan minimizar, en la medida de lo posible, las alteraciones causadas en el proceso.

La elección del tipo de proyección a utilizar en un caso determinado dependerá principalmente de dos factores:
1. La zona de la superficie terrestre que se quiera representar.
2. La especialización del mapa, es decir, la finalidad para la que se construya. Éste es un factor clave, ya que el uso de una proyección concreta puede evitar determinadas distorsiones geométricas que dificulten la utilización práctica del mapa.

## 3.2.2 Clasificación.

Las proyecciones cartográficas se pueden clasificar de diferentes maneras:
- a. Atendiendo al tipo de magnitud geométrica que el mapa sea capaz de conservar respecto a la real.
- b. Atendiendo a la forma de proyección

Atendiendo al tipo de magnitud geométrica que el mapa sea capaz de conservar respecto a la real.
- **Proyecciones conformes**.
	- Conserva el ángulo entre dos puntos medidos en la superficie de referencia y el mapa. 
	- ![[196-PROYECCIONES-CONFORMES.jpg]]
- **Proyecciones equivalentes**.
	- Conserva la proporcionalidad entre las áreas. A este respecto, es necesario aclarar que la equivalencia no es posible sin deformar considerablemente los ángulos originales. Por lo tanto, ninguna proyección puede ser equivalente y conforme a la vez.
	- ![[197-PROYECCIONES-EQUIVALENTES.jpg]]
- **Proyecciones equidistantes**.
	- Guardan la proporcionalidad entre las distancias. En la práctica, no existe ninguna proyección capaz de conservar esta propiedad a lo largo de todo el mapa. Sin embargo, puede conservarse a lo largo de determinadas líneas que se denominan automecoicas.
	- ![[198-PROYECCIONES-EQUIDISTANTES.jpg]]
- **Proyecciones afilácticas**.
	- No poseen ninguna de las tres propiedades señaladas.
	- ![[199-PROYECCIONES-AFILACTICAS.jpg]]

Está matemáticamente demostrado que no existe ningún sistema de proyección en el que se mantengan las tres dimensiones, sino solamente una de ellas.
- Atendiendo a la forma de proyección:
	- Se dividirán en:
		1. Proyecciones puras.
		2. Proyecciones modificadas.

**PROYECCIONES PURAS**.
- Resultan de la verdadera proyección geométrica de la superficie terrestre, o parte de ella, sobre un plano o una superficie desarrollable.
- Proyecciones planas o perspectivas.
	- Resultan de la proyección geométrica de los puntos de la superficie terrestre sobre un plano.
	- Según el lugar donde se sitúe el centro de proyección.
		- Ortográficas.
			- El foco de proyección se encuentra fuera de la superficie terrestre y a una distancia infinita de la misma.
			- ![[200-PROYECCION-ORTOGRAFICA.jpg]]
		- Escenográficas.
			- El foco de proyección se encuentra fuera de la superficie terrestre, a una distancia finita.
			- ![[201-PROYECCION-ESCENOGRAFICA.jpg]]
		- Estereográficas.
			- Cuando el foco de proyección se encuentra sobre la superficie terrestre. 
			- ![[202-PROYECCION-ESTEREOGRAFICA.jpg]]
		- Gnomónicas.
			- El foco de proyección se encuentra en el centro de la superficie terrestre.
			- ![[203-PROYECCION-GNOMONICAS.jpg]]
- Proyecciones por desarrollo.
	- Resultan de la proyección geométrica de los puntos de la Tierra sobre una superficie desarrollable.
	- TIPOS.
		- Cónicas: aquéllas en las que la superficie de proyección es un cono tangente o secante a la superficie terrestre de referencia. Dependiendo de la posición relativa de la superficie de proyección.
			- Directa.
				- El eje de la superficie de proyección es paralelo al eje de rotación terrestre.
				- ![[204-PROYECCION-CONICA-DIRECTA.jpg]]
			- Transversal.
				- El eje de la superficie de proyección es perpendicular al eje de rotación terrestre.
				- ![[205-PROYECCION-CONICA-TRANSVERSAL.jpg]]
			- Oblicua.
				- El eje de la superficie de proyección forma un ángulo comprendido entre 0º y 90º con el eje de rotación.
				- ![[206-PROYECCION-CONICA-OBLICUA.jpg]]
		- Cilíndricas: aquéllas en las que la superficie de proyección es un cilindro tangente o secante a la esfera. Dependiendo de la posición relativa de la superficie de proyección.
			- Directa.
				- El eje de la superficie de proyección es paralelo al eje de rotación terrestre.
				- ![[207-PROYECCION-CILINDRICA-DIRECTA.jpg]]
			- Transversal. 
				- El eje de la superficie de proyección es perpendicular al eje de rotación terrestre.
				- ![[208-PROYECCION-CILINDRICA-TRANSVERSAL.jpg]]
			- Oblicua.
				- El eje de la superficie de proyección forma un ángulo comprendido entre 0º y 90º con el eje de rotación.
				- ![[209-PROYECCION-CILINDRICA-OBLICUA.jpg]]

**PROYECCIONES MODIFICADAS**.

Recurren a distintos artificios geométricos y analíticos para conseguir que una determinada proyección pura adquiera alguna propiedad que no posea originariamente, con el fin de disminuir las distorsiones geométricas en determinadas áreas que resulten de interés para el uso de la carta.

En la actualidad, la mayoría de los mapas se hacen a base de proyecciones modificadas. Entre las más populares se encuentran las proyecciones de Bonne, Lambert, Mercator, Mollweide,

## 3.2.3 Aplicación de las proyecciones cartográficas en la aeronáutica.

Las proyecciones cónicas tienen un uso muy extendido en la cartografía aeronáutica, especialmente en lo referido a la navegación en ruta, debido a la facilidad y exactitud con la que se pueden representar las trayectorias.

Las cónicas más utilizadas son las gnomónicas-directas, en las que el plano cónico es tangente a la superficie terrestre a lo largo de un paralelo que se denomina estándar.

Este tipo de proyección tiene varias características importantes:
1. Los meridianos se transforman en rectas concurrentes en el Polo y los paralelos en arcos de circunferencias concéntricas en el punto de concurrencia de los meridianos. Ambos tipos de línea mantienen un ángulo constante de 90º.
2. La proyección es conforme, por su propia construcción, a lo largo de toda la representación. Las distorsiones lineales y superficiales son mínimas en las inmediaciones del paralelo estándar (único automecoico, es decir, sin deformación lineal) y aumentan según se aleja de esta línea.

La proyección cónica conforme de Lambert es una proyección modificada que se basa en la directa-gnomónica, pero sustituye el cono tangente por uno secante.

Lambert calculó matemáticamente la posición de los paralelos de corte del cono de proyección con la superficie terrestre:
- a. Consiguiéndose dos paralelos estándares automecoicos.
- b. Logrando que las deformaciones lineales queden reducidas a la mitad del valor absoluto de las que se producirían en el caso de usar un cono tangente.

De este modo, no sólo se mantiene una constancia en la escala bastante extendida en la carta, sino que, además, por ser ésta conforme, la distorsión de las áreas es mínima.

![[210-PROYECCION-CONICA-LAMBERT.jpg]]

La proyección cónica conforme de Lambert resulta de enorme utilidad para la navegación aérea por diversos motivos:
- Al tratarse de una carta conforme y prácticamente equidistante, se pueden medir los rumbos y las distancias directamente sobre ella con bastante precisión.
- La ortodrómica se representa -con gran aproximación- por una recta, por lo que el trazado de una ruta de estas características puede realizarse uniendo directamente los puntos sobre la carta.
- La loxodrómica está representada por una curva con la concavidad orientada hacia el vértice de la proyección.