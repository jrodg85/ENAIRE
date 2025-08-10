
# 4.1 Descripción de los sistemas de vigilancia.

## 4.1.1 Sistemas de vigilancia no cooperativa.

### 4.1.1.1 Radar Primario (PSR).

El PSR (Primary Surveillance Radar / Radar Primario de Vigilancia) es un sistema de vigilancia independiente no cooperativo capaz de proporcionar la distancia y azimut al «blanco», es decir, a la aeronave.

### 4.1.1.2 Principio de funcionamiento.

El PSR sólo consta de componente terrestre ya que, al ser un sistema independiente no coopoerativo, no requiere de equipos específicos a bordo de la aeronave.

![[273-PRINCIPIO-FUNCIONAMIENTO-RADAR.jpg]]

A través de una antena giratoria, la instalación terrestre transmite a intervalos regulares una serie de impulsos de radiofrecuencia (denominados señales de interrogación) que -al ser reflejados en el blanco- vuelven a ser recibidos y procesados, proporcionando la siguiente información:
- **Distancia del blanco respecto a la estación terrestre**: Este parámetro se obtiene a partir de la medida del tiempo transcurrido desde que se envía la señal de interrogación hasta que recibe la señal reflejada en el blanco.
- **Marcación angular del blanco**: Este parámetro se obtiene a partir del ángulo de posición de la antena en el instante de recepción de la señal reflejada.
- **Tiempo de la detección**: Instante en el que el blanco fue detectado.

![[274-REPRESENTACION-FUNCIONAMIENTO-RADAR.jpg]]

### 4.1.1.3 Equipo de tierra PSR.

El equipo PSR se compone básicamente de un sistema antena-transmisor-receptor, encargado de emitir y procesar las señales, así como el equipamiento de comunicaciones necesario para enviar allí donde es necesaria la presentación de la información de vigilancia obtenida.

![[275-REPRESENTACION-UNIDAD-INDICADORA-PSR.jpg]]

![[276-CONSOLA-RADAR-PRIMARIO.jpg]]

### 4.1.1.4 Características operacionales.
El PSR trabaja en las bandas de frecuencia L (de 1 a 2 GHz) y S (de 2 a 4 GHz).

Utiliza ondas electromagnéticas que viajan esencialmente en línea recta y son fácilmente reflejadas por los objetos que se encuentran en su trayectoria.

Los servicios de tránsito aéreo utilizan este tipo de radar para obtener información de la situación del tráfico aéreo tanto en ruta como en aproximación y detección de movimientos en el área de maniobras.

Aparte de efectuar la vigilancia de aeronaves, el PSR también se emplea para la detección de fenómenos meteorológicos.

Los inconvenientes que se presentan al trabajar con este radar son debidos a imprecisiones en la identificación y pérdidas de señales como consecuencia de reflejos producidos por el terreno.

### 4.1.1.5 Radar de movimiento en superficie (SMR).

El radar de movimiento en superficie (SMR) es un equipo radar diseñado específicamente para detectar el tráfico de aeronaves y vehículos en la superficie de un aeropuerto y para presentar la imagen completa en una consola indicadora en la torre de control. Se utiliza para mejorar la observación visual por parte del personal de la torre de aeronaves y/o movimientos de vehículos en pistas y calles de rodaje.

- Principio de funcionamiento.
	- El SMR utiliza el principio de funcionamiento del radar primario de vigilancia (PSR), es decir, emite una señal que se refleja en el objetivo y el eco recibido se utiliza para determinar la posición (distancia y acimut) del blanco.
- Equipo de tierra SMR.
	- El equipo SMR, al igual que el PSR, se compone de una antena transmisora-receptora y del equipamiento necesario para generar la señal, procesar el eco recibido y presentar la información de vigilancia obtenida.

![[277-ANTENA-SMR-SOBRE-TORRE.jpg]]

![[278-RADAR-DE-SUPERFICIE.jpg]]

### 4.1.1.6 Características operacionales.

El SMR opera en la banda de frecuencia X (de 8 a 12 GHz).

En comparación con el PSR, la antena es mucho más pequeña y liviana, lo que permite una rotación más rápida (normalmente 1 revolución por segundo en lugar de 6-15 revoluciones por minuto) y, por lo tanto, tiene una tasa de actualización del dato más rápida.

La resolución de acimut también se mejora (precisión de 0,25 grados) en comparación con el PSR (1-2 grados) debido al ancho de haz más delgado (que se logra debido a la mayor frecuencia utilizada).

El alcance operativo es considerablemente más pequeño si se compara con otros radares (lo que no debe considerarse un inconveniente, ya que el propósito del SMR es cubrir solo el área de maniobras), lo que permite usar pulsos más cortos, lo que resulta en una resolución en distancia mucho mejor (unos 20 m).

## 4.1.2 Sistemas de vigilancia cooperativa.
### 4.1.2.1 Radar secundario (SSR).

El SSR (Secondary Surveillance Radar / Radar Secundario de Vigilancia) es un sistema de vigilancia independiente cooperativo, capaz de proporcionar información de posición de una aeronave.

Este radar se desarrolló para aumentar las prestaciones de los radares primarios, pero no significa que uno sea sustituto del otro, sino más bien complementarios. El radar secundario presenta mayor inmunidad a los fenómenos atmosféricos y facilita la vigilancia en cualquier condición meteorológica, además de mejorar la precisión en la marcación angular (mediante el empleo de la técnica monopulso).

### 4.1.2.2 Principio de funcionamiento.

El SSR consta de un componente terrestre y un equipo de a bordo en la aeronave, denominado transpondedor. Existen distintos modos de radar secundario en función de la información que proporcionan las aeronaves, como identificación de la aeronave, altitud, etc.

En este sistema, el blanco a detectar interviene activamente en el proceso de vigilancia. Una vez la aeronave recibe la señal emitida desde una estación en tierra, esta señal es procesada a bordo y enviada de vuelta a la estación de tierra, proporcionando la siguiente información:
- Distancia respecto a la estación terrestre.
- Tiempo de la detección
- Marcación angular.
- Altitud de la aeronave.
- Situaciones de emergencia (fallo, secuestro, etc.).
- Identificación de la aeronave (incluyendo compañía y número de vuelo).
- Información relativa a la intención de la aeronave: nivel de vuelo seleccionado, reporte de giro, rumbo y velocidad.

![[279-RADAR-SECUNDARIO.jpg]]

### 4.1.2.3 Equipo de tierra SSR.

Al igual que en el radar primario consta de un sistema antena-transmisor-receptor, encargado de emitir y procesar las señales que presentan al usuario la información de vigilancia, a través de una unidad indicadora.

Este equipo puede emitir señales que “interrogan” a las aeronaves de diferentes modos, en función de la información que se requiera, normalmente identificación y altitud de la aeronave.

### 4.1.2.4 Equipo de a bordo.

La generación de una respuesta a bordo de la aeronave implica la necesidad de que el avión vaya equipado de un sistema específico, llamado transpondedor o respondedor. Este equipo dota al radar secundario de la capacidad que permite que el avión sea seguido e identificado fácilmente desde tierra.

En la siguiente tabla se especifican los diferentes modos de trabajo del transpondedor siendo el modo S el de mayor uso:

| MODO         | APLICACIÓN                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| MODO 3/A<br> | El equipo de a bordo transmite una señal de identificación, que cuando es requerida por el control de tierra, hace que se ilumine en la pantalla radar con mayor intensidad el «blanco» que representa el avión.                                                                                                                                                                                                                               |
| MODO C       | Con este modo conectado, además de estar seleccionado el Modo 3/A, el equipo transmite una señal de altitud (lo que equivale al nivel de vuelo), que aparecerá en la pantalla radar.                                                                                                                                                                                                                                                           |
| INTERMODO    | 1. Interrogación en Modos A, C y S. De esta forma se obtendrán respuestas para vigilancia de respondedores en los Modos A/C y S.<br>2. Interrogación en Modo A y C solamente. De esta forma se obtienen respuestas para vigilancia de respondedores en Modos A/C.                                                                                                                                                                              |
| MODO S       | 1. Interrogación en Modo S General: para obtener respuestas sólo en Modo S.<br>2. Radiodifusión: para transmitir información a todos los respondedores en Modo S. No se obtienen respuestas.<br>3. Llamada Selectiva: para vigilancia de determinados respondedores en Modo S y para la comunicación con ellos. Para cada interrogación, se obtiene una respuesta solamente del respondedor al que se ha dirigido una interrogación exclusiva. |

La operación en Modo S permite controlar un gran número de aeronaves, mejorando la exactitud de la información y la rapidez en las transmisiones tierra-aire-tierra, permitiendo el intercambio de información específica con cada usuario, mediante las llamadas selectivas.
El Modo S mejora la capacidad de suministrar información adicional, como indicadores de emergencia.

### 4.1.2.5 Características operacionales.

El radar secundario establece mejores intercambios de información entre el equipo de tierra y el avión, debido principalmente a que las señales transmitidas desde las aeronaves son claras y potentes, lo que permite que sean bien captadas por el equipo de tierra evitando que se distorsione o pierda información.

El hecho de que el «blanco» sea de carácter cooperativo tiene tres efectos principales:
- No se requieren potencias tan elevadas como las del radar primario.
- El receptor no requiere sensibilidades grandes.
- Puede intercambiarse información entre los equipos de tierra (interrogador) y a bordo (respondedor), pudiendo ser la comunicación iniciada desde tierra o desde el aire.

### 4.1.2.6 Sistemas de multilateración.

La multilateración (MLAT) es un sistema de vigilancia independiente cooperativo, capaz de proporcionar información de posición de una aeronave. Se puede utilizar para la vigilancia del tráfico terrestre (entorno del aeródromo) y aéreo. Los sensores MLAT (transmisores/receptores) se pueden ubicar dentro de los límites del aeropuerto para vigilancia terrestre, en y cerca de un aeropuerto para monitorear el tráfico de llegada y salida o sobre un área extensa, donde un radar convencional (PSR o SSR) no es práctico o posible, para monitorear el tráfico en ruta.

**Principio de funcionamiento**.
- Se basa en una metodología conocida como diferencia horaria de llegada (TDOA, por las siglas en inglés de Time Difference of Arrival)) que se puede utilizar de dos maneras, bien la señal de una unidad móvil se mide en una serie de ubicaciones fijas conocidas, o bien las señales de una serie de ubicaciones fijas son medidas por un receptor móvil. La TDOA de las señales en el o los receptores permite determinar la posición de la entidad móvil.
- En respuesta a una señal de interrogación de uno de los transmisores MLAT, el transpondedor del vehículo o avión transmitirá una respuesta que será recibida y procesada por todas las estaciones MLAT en su área de cobertura. La variación de TDOA en los diversos sitios terrestres permitirá una determinación precisa de la posición del vehículo o aeronave.
- Matemáticamente, conociendo el tiempo que tarda en llegar la señal a una estación se genera una esfera donde podría encontrarse la aeronave. Si la señal se recibe en dos estaciones, la intersección de esas dos esferas genera una curva hiperbólica sobre la cual la aeronave podría situarse. Agregar una tercera estación receptora reduce toda esa curva hiperbólica a dos posibles puntos específicos de ubicación, uno de los cuales, normalmente, puede descartarse como improbable. Añadir un cuarto punto de recepción daría como resultado una única posición calculada para el emisor de la señal.
**Equipo de tierra MLAT**.
- Consta de varias estaciones distribuidas a lo largo del área de vigilancia a la que se quiere prestar servicio, estando encargadas de emitir las señales de interrogación y procesar las respuestas, así como del equipamiento que completa el procesado de la información y permite presentar al usuario dicha información de vigilancia.

![[280-ESTACION-MULTILATERACION.jpg]]

![[281-PANTALLA-VISUALIZACION-DATOS-MULTILATERACION.jpg]]

### 4.1.2.7 Equipo de a bordo.

La generación de una respuesta a bordo de la aeronave o de los vehículos circulando por el área de interés implica la necesidad de que estos estén equipados con transpondedores, exactamente igual que ocurre en el radar secundario de vigilancia.

#### 4.1.2.8 Características operacionales.

Al igual que ocurre con el radar secundario, el hecho de que se trate de una vigilancia cooperativa permite el intercambio de información entre las estaciones de tierra y el avión o los vehículos, y dado que las respuestas recibidas por las estaciones de tierra son claras y potentes, se evita o minimiza la posible pérdida de información. Además, se pueden minimizar las áreas sin cobertura, añadiendo o modificando la posición de las estaciones de tierra.

## 4.1.3 SISTEMA DE VIGILANCIA DEPENDIENTE AUTOMÁTICA.

La Vigilancia Dependiente Automática (ADS) es una técnica de vigilancia por la que una aeronave transmite, a través de enlace de datos, una serie de parámetros extraídos de los sistemas de navegación y posicionamiento de a bordo.

### 4.1.3.1 Principio de funcionamiento.

La técnica ADS requiere un sistema de posicionamiento y navegación y un enlace de datos a bordo del avión, y en tierra, estaciones que reciban la información ADS para que pueda ser transmitida y utilizada por los sistemas de tratamientos de datos de vigilancia.

La técnica ADS proporciona:
- La identificación de la aeronave.
- La posición de la aeronave dimensiones.
- Información adicional, como la velocidad.

### 4.1.3.2 Tipos de ADS.

ADS-C: La vigilancia dependiente automática - Contrato (ADS-C) es una técnica de vigilancia en la cual las aeronaves, mediante un enlace de datos, suministran a los sistemas de tierra (por ejemplo, centros de control de tránsito aéreo) datos tales como posición e identificación, derivados de los sistemas de aviónica de a bordo. Para ello, se establece un acuerdo ("contrato") entre la aeronave y el citado sistema de tierra, que establece las condiciones bajo las cuales la información será transmitida: forma periódica y/o bajo la ocurrencia de una determinada circunstancia, como puede ser el sobrevuelo de fijos establecidos en los sistemas embarcados de la aeronave como parte de su plan de vuelo. El sistema de tierra también tiene la capacidad de obtener información en cualquier momento mediante los denominados contratos bajo demanda.

ADS-B: La vigilancia dependiente automática – Radiodifusión (ADS-B) es una técnica de vigilancia que permite la transmisión de parámetros derivados de la aeronave, como posición e identificación, a través de un enlace de datos en modo de radiodifusión, para ser utilizados por cualquier usuario convenientemente equipado en el aire y/o en tierra.

### 4.1.3.3 Características operacionales.

La ADS tiene dos características definitorias fundamentales:
- es automática, es decir, no necesita la intervención del piloto para que los datos de la aeronave sean enviados a los servicios de tránsito aéreo, y
- es dependiente, porque la información necesaria es generada en la misma aeronave, es decir, depende de los sistemas de a bordo.

Este nuevo sistema es esencial para mejorar la vigilancia en zonas oceánicas (a día de hoy mediante ADS-C, aunque se está considerando el uso de ADS-B vía satélite) y en zonas continentales en las que no se dispone de cobertura radar, así como para mejorar y racionalizar la vigilancia en zonas actualmente cubiertas con radar, mediante el despliegue de estaciones ADS-B.


