
# 2.5 Sistemas de referencia terrestre.

El trazado de un mapa requiere el establecimiento de un método que permita localizar puntos concretos de la superficie terrestre, para su posterior representación.

Con este objetivo, se han desarrollado diferentes modelos matemáticos caracterizados básicamente por:
1. Un sistema de coordenadas, que permite posicionar puntos sobre el elipsoide.
2. Datum: Conjunto de parámetros que fijan el origen, la orientación y la escala del sistema de coordenadas con respecto a un elipsoide de referencia (un modelo asociado de la forma de la tierra).

## 2.5.1 Sistema de coordenadas geográficas.

El sistema de coordenadas geográficas es uno de los métodos más utilizados en la determinación de puntos sobre la superficie terrestre. Dicha localización se realiza mediante dos distancias angulares tomando como referencia una aproximación esférica de la Tierra: Longitud y Latitud.

**LATITUD**.

Se llama latitud de un punto de la superficie terrestre a la distancia angular, medida en grados sobre un meridiano, entre dicho punto y el Ecuador, que es la línea que se toma como origen de latitudes. Se mide en grados, minutos y segundos. Varía de 0º a 90º y puede ser:
- Norte o positiva (N): si el punto se encuentra por encima del Ecuador.
- Sur o negativa (S): si el punto se encuentra por debajo del Ecuador.

Según la definición de latitud, los puntos situados sobre el Ecuador tienen como latitud 0º y los Polos tienen como latitud 90º, por tanto, todos los puntos de un mismo paralelo tienen la misma latitud.

![[189-LATITUD.jpg]]

**LONGITUD**.

Se llama longitud de un punto a la distancia angular, medida en grados sobre el Ecuador, entre el meridiano del lugar y el meridiano de origen o de Greenwich. Se mide en grados, minutos y segundos. Varía de 0º a 180º y puede ser:
- Este o positiva (E): si el punto se sitúa a la derecha del meridiano origen.
- Oeste o negativa (W): si el punto se sitúa a la izquierda del meridiano origen.

Según la definición de longitud, los puntos situados en el meridiano origen tienen como longitud 0º, por tanto, todos los puntos situados en un mismo meridiano tienen la misma longitud.

![[190-LONGITUD.jpg]]

## 2.5.2 Datum WGS84.

La ambigüedad en el cálculo de coordenadas, ocasionada por el uso de diferentes datums, puso de manifiesto la necesidad de normalizar un modelo único de referencia que pudiera ser utilizado en diferentes aplicaciones.

Con este objetivo, el Departamento de Defensa estadounidense desarrolló el World Geodetic System 1984 (WGS84), un sistema de referencia geodésico universal con cobertura para toda la superficie terrestre, definido por los siguientes parámetros:
1. Origen: centro de masas de la Tierra. Sistemas de ejes coordenados:
2. Eje Z: dirección del polo medio convencional terrestre definido por el IERS (Servicio Internacional de Rotación de la Tierra), perpendicular al plano fundamental (Ecuador medio). Coincidente con el eje medio de rotación de la Tierra.
3. Eje X: formado por la intersección determinada por el plano del Ecuador y el meridiano de Greenwich también definido por el IERS.
4. Eje Y: situado sobre el plano del Ecuador medio y a 90° a la derecha del eje X formando junto con el eje Z un triedro a derechas siendo el origen del triedro el centro de masas de la Tierra.
5. Elipsoide WGS84: elipsoide de revolución definido por los parámetros:
	- Semieje mayor (a) = 6 378 137 m.
	- Semieje menor (b) = 6 356 752 m.
	- Constante de Gravitación Terrestre: GM = (3986004.418 ± 0.008) x 108 m3 / s2. Velocidad angular: W= 7292115 x 10-11 rad/s.
	- Coeficiente de forma dinámica: J2= -484,166 85 x 10-6.

![[191-WGS84.jpg]]

Las coordenadas aeronáuticas publicadas en el AIP-ESPAÑA están referidas al sistema geodésico WGS84, de acuerdo con lo establecido en el Anexo 15 de la OACI. El Real Decreto 1071/2007, de 27 de julio, adaptación del mandato de la Comisión Europea de 1999, por el que se regula el sistema geodésico de referencia oficial en España, establece que se adopta el sistema ETRS89 (European Terrestrial Reference System 1989) como sistema de referencia geodésico oficial en España para la referenciación geográfica y cartográfica en el ámbito de la península Ibérica y las Islas Baleares. En el caso de las islas Canarias, se adopta el sistema REGCAN95.

Ambos sistemas tienen asociado el elipsoide GRS80 (Sistema de Referencia Geodésico 1980) y están materializados por el marco que define la Red Geodésica Nacional por Técnicas Espaciales, REGENTE, y sus densificaciones. Inicialmente, teniendo en cuenta la exactitud requerida para los diferentes datos establecidas en el Catálogo de Datos Aeronáuticos, ETRS89 y REGCAN95 se consideraron equivalentes a WGS84.

Sin embargo, debido a la deriva existente entre estos sistemas, se han hallado discrepancias cada vez mayores que la exactitud requerida para algunos datos, por lo que los sistemas ETRS89 y REGCAN95 no se pueden considerar válidos para la publicación de coordenadas en AIP ESPAÑA.