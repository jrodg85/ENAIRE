
# 3.4 Tratamiento de los planes de vuelo dentro del proceso ATFCM.

Los planes de vuelo son tratados por el Sistema Integrado para el Tratamiento Inicial de Planes de Vuelo (IFPS), una unidad englobada dentro del Gestor de red (NM Network manager), que consta de dos centros redundantes: Bruselas y Bretigny (Paris). España depende de la sede francesa, generalmente.

El IFPS se encarga:
- De recepcionar los planes de vuelo.
- Del procesado inicial (validación).
- De la distribución de los datos de Plan de Vuelo, en el área ECAC, a las unidades ATC para que puedan ser tratados automáticamente por los sistemas de cada proveedor de servicios de Navegación (ANSP Air Navigation Service Provider).
- De proporcionar a operaciones del Gestor de red (NM Network Manager) información sobre datos de plan de vuelo (FPL) para la planificación ATFCM, monitorización y asignación de slot.

![[284-IPFS.jpg]]

La centralización de la información en una única base de datos permite garantizar la coherencia, homogeneidad y compatibilidad de los datos utilizados por todos los sistemas del Gestor de red (NM Network Manager). La fiabilidad y efectividad de todos estos sistemas se asienta en la exactitud de los datos aportados a la base de datos (ENV).

Los planes de vuelo recibidos por el IFPS son contrastados con la información de a la base de datos ENV de forma automática.

**FPL rechazado (REJ)**.

Si el plan de vuelo incluye información contraria a la contenida en base de datos ENV será rechazado por el sistema (REJ).

**FPL aceptado (ACK)**.

Si la información del plan de vuelo es correcta o permite que el error sea corregido manualmente, será aceptado por el sistema (ACK) y enviada a los proveedores de servicios de Navegación (ANSP: Air Navigation Service Provider) correspondientes.

La solución al problema pasa por detectar cuál de las modificaciones que entran en vigor ese día es la que afecta a estos planes de vuelo.

Los PLN rechazados no llegan a ATC y es tarea del operador o el originador del mensaje tomar medidas al respecto.

**Plan de vuelo suspendido (FLS)**.

En ocasiones ocurre que un plan de vuelo, pese a haber sido aceptado con anterioridad, se suspende por alguna causa mediante el envío de un mensaje de suspensión del vuelo (FLS Flight suspension message). Este mensaje será recibido en la dependencia ATS e inicialmente implica la no autorización de salida del vuelo.


