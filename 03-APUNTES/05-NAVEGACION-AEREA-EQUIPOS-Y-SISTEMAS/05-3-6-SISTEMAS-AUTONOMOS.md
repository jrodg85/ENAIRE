
# 3.6 Sistemas autónomos.

# 3.6.1 Sistema de Navegación inercial (ins).

El INS (Inertial Navigation System / Sistema de Navegación Inercial) es un sistema de ayuda a la navegación que proporciona a una aeronave debidamente equipada información de posición que permita determinar la situación exacta del avión.

Además de proporcionar información sobre la situación de una aeronave en vuelo, el INS proporciona velocidad con respecto a tierra, posición instantánea y distancia a un destino u objeto preestablecido.

### 3.6.1.1 Principio de funcionamiento.

El principio de funcionamiento del INS se basa en la detección a bordo, de las aceleraciones que sufre la aeronave, mediante una plataforma estabilizada en dos ejes orientados permanentemente hacia el Norte y Este geográfico. Si la aceleración detectada se integra a lo largo del tiempo, se obtiene la velocidad de la aeronave respecto al suelo (GS) según esos ejes.

De forma análoga, si se integran las componentes de la velocidad según los ejes indicados a lo largo del tiempo, se obtendrá la distancia recorrida según esas direcciones en el tiempo de integración. Sumando a la coordenada inicial el incremento de posición obtenido de esta integración, se obtendrá la nueva posición.

Es importante indicar la necesidad de conocer las coordenadas del punto inicial del vuelo, en este sentido, el piloto de la aeronave, previamente a comenzar la utilización del INS para navegar introduce la coordenada inicial (aeropuerto de origen).

### 3.6.1.2 Equipo de a bordo.

El equipo de a bordo es el encargado del cálculo de la posición a través de una plataforma inercial sensible a los movimientos del avión con respecto a la superficie terrestre. Esta plataforma envía la información a un computador que la presenta en los instrumentos de navegación.

Los cuatro componentes básicos de un INS convencional son:
- Acelerómetros: Dispositivos situados sobre una plataforma inercial, encargados de medir las componentes del vector aceleración.
- Plataforma inercial: Aparato encargado de mantener los acelerómetros paralelos a la superficie terrestre, proporcionando una referencia direccional.
- Integradores: Dispositivos encargados de recibir la señal de salida de los acelerómetros, transformándola en señales de velocidad y distancia recorrida sucesivamente.
- Computador: Aparato que recibe las señales de salida de los integradores y las transforma en datos de posición (coordenadas geográficas; latitud y longitud), velocidad sobre el suelo y otras informaciones útiles.

### 3.6.1.3 Características operacionales.
El INS se concibe como un sistema que, con los vectores de aceleración y gravitación se obtiene la situación de una aeronave, por lo tanto tiene que actualizarse constantemente la información.

Las actualizaciones del INS son necesarias porque el sistema está sujeto a un error sistemático, es decir el error va creciendo a medida que aumenta el tiempo desde su última actualización, lo que hace necesario que ésta se realice de forma periódica mediante la utilización de otro sistema, como podría ser un VOR, VOR/DME, GPS, etc.

Los aviones de nueva tecnología van equipados con Sistemas Inerciales de tipo láser, cuyos componentes básicos respecto a los INS convencionales tienen, pero a diferencia de los anteriores mede velocidades angulares. Este tipo de Inerciales constan de tres giróscopos láser y tres acelerómetros, orientado cada uno hacia uno de los tres ejes principales del avión, de modo que puedan «sentir» tanto la rotación del avión alrededor de cada eje como la aceleración a lo largo del mismo.

![[271-EJES-PRINCIPALES-AVION.jpg]]

## 3.6.2 Radar Doppler.
El Radar Doppler es un sistema de ayuda a la navegación que proporciona al piloto la posición del avión respecto a una ruta seleccionada.

### 3.6.2.1 Principio de funcionamiento.

La determinación de la situación de un avión, respecto de la superficie terrestre, se realiza por el clásico proceso de la navegación a estima, es decir, por sumas sucesivas de los incrementos de espacio recorrido, que se obtienen mediante los productos de las velocidades por los incrementos de tiempo.

Este sistema se basa en la emisión de energía electromagnética generada en la aeronave y recibida por la misma, tras su reflexión en la superficie terrestre.

### 3.6.2.2 Equipo de a bordo.

El Radar Doppler consiste en un transmisor de señales localizado en el avión que dirige hacia el suelo tres o cuatro haces de ondas electromagnéticas.

Las ondas emitidas son reflejadas por la superficie de la tierra y una porción de la energía reflejada es recibida por un receptor de ondas situado también en el avión.

La información recibida es procesada por el computador de a bordo, que a través de un instrumento visual proporciona la distancia transversal a la ruta preseleccionada y la distancia por recorrer a lo largo de la ruta.

![[272-HACES-DE-ONDAS-AVION.jpg]]

### 3.6.2.3 Características operacionales.

Por la técnica utilizada (basada en la variación de frecuencia entre señales emitidas y recibidas), la aceleración sólo puede ser calculada sin ambigüedad en un determinado rango de velocidades de la aeronave, lo que genera una reducción de la distancia máxima de operación del sistema.

