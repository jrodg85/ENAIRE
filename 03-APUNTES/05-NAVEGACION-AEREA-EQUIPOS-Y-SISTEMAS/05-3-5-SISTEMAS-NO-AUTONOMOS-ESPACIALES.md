
# 3.5 Sistemas no autónomos, espaciales.

## 3.5.1 Sistemas de Navegación por Satélite.

Los sistemas GNSS (Global Navigation Satellite System / Sistema Global de Navegación por Satélite) proporcionan con mucha exactitud la posición (metros) y el tiempo (nanosegundos) en todo el mundo.

### 3.5.1.1 Principio de funcionamiento de las constelaciones principales GNSS.

El principio de funcionamiento de las constelaciones principales GNSS se basa en la medida del tiempo que tarda una señal en llegar desde el emisor (satélite) al receptor (aeronave), proporcionando la distancia entre ambos.

Midiendo la distancia a tres satélites se determina la posición del receptor en el espacio y en el tiempo, a partir del conocimiento de la posición de los satélites, la cual es controlada en todo momento por las estaciones de tierra. En la práctica se requiere un cuarto satélite para sincronizar el reloj del receptor y así medir la distancia a los satélites con precisión.

![[269-REPRESENTACION-ESQUEMATICA-GNSS.jpg]]

### 3.5.1.2 Descripción de las constelaciones principales GNSS.

Los sistemas GPS (Global Positioning System / Sistema de Posicionamiento Global), GLONASS (Global Navigation Satellite System / Sistema de Navegación por Satélite), GALILEO y BeiDou/BDS están constituidos por tres segmentos operativos (espacial, terrestre o de control y de usuario):

![[270-REPRESENTACION-CONSTELACIONES-GNSS.jpg]]

- SEGMENTO ESPACIAL: formado por una constelación de satélites encargados de transmitir señales de radiofrecuencia con mensajes de navegación a partir de los cuales se calcula la posición del receptor.
- SEGMENTO TERRESTRE O DE CONTROL: formado por estaciones terrestres cuya misión principal es la de controlar y supervisar el buen funcionamiento de la constelación de satélites, aunque también puede proporcionar servicios de valor añadido como datos de integridad, y servicios de búsqueda y rescate.
- SEGMENTO DE USUARIO: formado por los receptores que captan y procesan las señales transmitidas por los satélites, proporcionando la posición y el tiempo a los usuarios (aeronaves).

### 3.5.1.3 Características operacionales.

Aunque el principio de funcionamiento de las constelaciones principales GNSS es similar en todas ellas, las frecuencias de las señales emitidas por los satélites, su modulación y la codificación del mensaje de navegación, pueden ser diferentes.

Se utilizan sistemas de aumentación para mejorar las prestaciones de navegación de las constelaciones principales GNSS, y así cumplir con los requisitos de integridad, disponibilidad, continuidad y exactitud exigidos en las diferentes fases de vuelo/operaciones.

### 3.5.1.4 Sistemas de Aumentación.

Para mejorar las prestaciones de navegación de las constelaciones principales GNSS (GPS, GLONASS, Galileo o BeiDou, o en el futuro una combinación de ellos) y hacerlos aptos para el uso en la navegación aérea, se desarrollan los sistemas de aumentación. Estos sistemas proporcionan correcciones y/o información de integridad al receptor (segmento usuario) que los usa para aumentar las prestaciones de exactitud, integridad, continuidad y disponibilidad del sistema GNSS. Cada sistema de aumentación tiene su área de servicio dentro de la cual se recibe y se puede usar su señal de aumentación. El uso de cada tipo de sistema de aumentación requiere capacidades específicas en los receptores/equipos de a bordo.

Existen tres tipos de sistemas de aumentación:

1. SBAS.
	- Siglas.
		- Sistema de aumentación basado en satélite / Satellite-based augmentation system.
	- Área de servicio.
		- Este sistema mejora las prestaciones de una constelación principal GNSS sobre un área de servicio amplia (región, continente).
	- Funcionamiento.
		- Enviando al usuario correcciones e información de integridad a través de satélites geoestacionarios. EGNOS es el SBAS desarrollado en Europa y da un servicio de aumentación sobre toda Europa.
	- Fases.
		- El sistema SBAS es compatible, aunque no obligatorio, con PBN en las fases de ruta, SID, STAR y aproximaciones de no precisión. Dependiendo donde nos situemos dentro de su área de servicio, puede llegar a habilitar aproximaciones con guiado vertical APV SBAS o de precisión CAT I, para las cuales sí resulta necesario.
2. GBAS.
	- Siglas.
		- Sistema de aumentación basado en tierra / Ground-based augmentation system.
	- Área de servicio.
		- Este sistema mejora las prestaciones de una constelación principal GNSS sobre un área de servicio local (cerca del aeropuerto en el que se instala).
		- Funcionamiento.
			- Emitiendo la información de aumentación a través de una o varias antenas VHF en tierra. Fases Habilita aproximaciones de precisión, actualmente CAT I y en el futuro CAT II/III.
3. ABAS.
	- Siglas.
		- Sistema de aumentación basado en la aeronave / Aircraft-based augmentation system.
	- Área de servicio.
		- Su área de servicio es global.
	- Funcionamiento.
		- Este sistema está embarcado en el avión y se basa en el uso de datos disponibles en los sistemas autónomos de la aeronave (como el sistema de referencia inercial (IRS) o el sistema de datos aire), o en la redundancia de las señales recibidas de los satélites del sistemas básicos (solo se necesitan señales de 4 satélites pero se reciben de muchos más la mayor parte del tiempo).
	- Fases.
		- Habilita PBN en todas las fases del vuelo, pero en aproximación sólo lo hace hasta las aproximaciones de no precisión y APV con guiado vertical baro-VNAV.

En el futuro estos sistemas de aumentación mejorarán las prestaciones del uso conjunto de más de una constelación principal GNSS, por ejemplo GPS + Galileo.

