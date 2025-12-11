

# 3.2 Sistemas de ayuda a la Navegación aérea.

## 3.2.1 Generalidades.

A lo largo de la historia, las necesidades determinadas por el desarrollo del transporte aéreo han propiciado el desarrollo de diferentes métodos que permitieran la navegación en los distintos escenarios en los que una aeronave se pudiera encontrar, bajo cualquier tipo de condiciones meteorológicas y de visibilidad.

Para cada fase de vuelo, se especifican unos requerimientos operacionales relacionados con las prestaciones que deben cumplir los sistemas de navegación que actúen en ella.

## 3.2.2 Clasificación por parámetros.

En función de los requisitos exigidos para una operación o fase de vuelo, un sistema de ayuda a la navegación podrá ser considerado como:
- Medio principal o primario: Sistema de ayuda a la navegación aprobado para una determinada operación o fase de vuelo que debe satisfacer los requisitos establecidos de precisión e integridad, sin necesidad de cumplir las condiciones de disponibilidad y continuidad en el servicio.
- Medio único: Sistema de ayuda a la navegación aprobado para una determinada operación o fase de vuelo que debe cumplir los cuatro requisitos de prestación del sistema.
- Medio suplementario: Sistema de ayuda a la navegación aprobado para una determinada operación o fase de vuelo que debe utilizarse juntamente con un sistema considerado como medio único. Debe satisfacer los requisitos de precisión e integridad, sin necesidad de cumplir las condiciones de disponibilidad y continuidad en el servicio.

## 3.2.3 Clasificación por técnicas que usan y por sus elementos.

**SISTEMAS NO AUTÓNOMOS**.
- Definición.
	- Aquellos que se componen de un equipo de a bordo capaz de calcular y proporcionar al piloto la información de navegación, a partir de los datos suministrados por una infraestructura externa a la aeronave.
- Tipos.
	- B. TERRESTRES.
		- Son aquellos que utilizan una infraestructura auxiliar constituida exclusivamente por instalaciones fijas terrestres.
		- Tipos.
			- Por radioayudas.
				- Aquellos cuya infraestructura externa a la aeronave está constituida exclusivamente por estaciones terrestres fijas, las cuales suministran la información de navegación mediante su codificación y emisión en señales de radiofrecuencia. Estas señales son captadas y decodificadas por el equipo de a bordo del sistema, proporcionando al piloto los datos de posición y guiado.
				- Tipos.
					- NDB.
					- VOR.
					- DME.
					- ILS.
			- Visuales.
				- Aquellos cuya infraestructura externa a la aeronave está constituida por agrupamientos de luces, que suministran la información de navegación mediante su disposición sobre el terreno y la utilización de códigos de colores. En este caso, no existe un dispositivo de a bordo específico, siendo el piloto de la aeronave quien debe interpretar la información proporcionada por los elementos luminosos.
				- Tipos.
					- Sistemas indicadores de pendiente de descenso Luces de aproximación.
	- C. ESPACIALES.
		- Aquellos cuya infraestructura externa a la aeronave incluye satélites. Estos sistemas, también denominados sistemas GNSS (Global Navigation Satellite System), en sus diferentes variantes (combinación de sistemas globales básicos y sistemas de aumentación), son la base de la implantación del concepto PBN. Aparte de los satélites, todos los sistemas espaciales (excepto los de aumentación ABAS) incluyen infraestructuras terrestres auxiliares.
		- Tipos.
			- Constelaciones principales GNSS / sistemas de aumentación ABAS.
				- Las constelaciones principales son conjuntos de satélites que proporcionan una cobertura global en toda la superficie terrestre. Cada satélite suministra información de navegación mediante su codificación y emisión en señales de radiofrecuencia. Estas señales son captadas y decodificadas por el equipo de a bordo del sistema, que cuando las recibe simultáneamente de 4 satélites o más, puede proporcionar al piloto los datos de posición y guiado. 
				- Todos los receptores certificados GNSS en aeronaves, capaces de generar posición y guiado a partir de las constelaciones, incluyen sistemas de aumentación ABAS integrados para alcanzar los requisitos de prestaciones mínimos exigidos por OACI.
			- Tipos.
				- GPS (EE.UU.).
				- GLONASS (Rusia).
				- Galileo (Unión Europea).
				- BeiDou / BDS (China).
	- B.ESPACIALES.
		- Tipos.
			- Sistemas de aumentación SBAS.
				- Sistemas de cobertura regional/continental, que utilizan una red de estaciones de referencia terrestres para calcular correcciones e información de integridad, partiendo de los datos recibidos de las constelaciones GNSS. Las correcciones y la información de integridad se envían a las aeronaves mediante satélites en órbita geoestacionaria (GEO).
				- Los receptores SBAS embarcados calculan posición y guiado combinando a bordo la posición obtenida directamente de las constelaciones con los datos emitidos por el sistema SBAS.
				- Tipos.
					- Existen varios sistemas SBAS en el mundo, con grados diferentes de desarrollo. Se pueden destacar:
						- WAAS (EE.UU.).
						- EGNOS (Unión Europea).
						- MSAS (Japón).
						- GAGAN (India).
			- Sistemas de aumentación GBAS.
				- Consisten en una estación terrestre situada en el aeropuerto al que presta servicio. La estación monitoriza las señales recibidas desde una constelación principal GNSS y transmite correcciones de pseudodistancia, parámetros de integridad y datos de definición de aproximaciones, localmente pertinentes, a las aeronaves en el área terminal, mediante radiodifusión de datos en VHF (VDB).
				- Los receptores GBAS embarcados calculan posición y guiado combinando a bordo la posición obtenida directamente de las constelaciones con los datos emitidos por el sistema GBAS.

**SISTEMAS AUTÓNOMOS**.
- Aquellos que se componen de un equipo de a bordo capaz de calcular y proporcionar al piloto la información de posición y guiado de la aeronave, basándose en la medición directa de diferentes parámetros de vuelo (velocidad, presión, etc.) y actitud (se denomina actitud de una aeronave a su posición respecto a sus ejes principales).
- Son sistemas de altas prestaciones que, al no requerir de una infraestructura externa a la aeronave, se suelen utilizar para la navegación en zonas donde no existe la cobertura de otro tipo de ayudas
- Tipos.
	- Radar Doppler.
	- Equipos inerciales (INS / Inertial Navigation Systems).