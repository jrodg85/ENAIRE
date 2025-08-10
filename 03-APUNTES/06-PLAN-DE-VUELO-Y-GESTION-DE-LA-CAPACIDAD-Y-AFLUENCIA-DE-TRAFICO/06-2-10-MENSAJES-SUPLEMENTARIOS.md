
# 2.10. Mensajes suplementarios.

Los mensajes suplementarios incluyen:

- Mensajes de solicitud de plan de vuelo RQP: 
	- Request Filed Flight Plan Message.
	- Se transmitirá un mensaje RQP cuando una dependencia ATS desee obtener datos de plan de vuelo. Esto puede ocurrir al recibirse un mensaje relativo a una aeronave para la cual no se hayan recibido los datos básicos de plan de vuelo correspondientes.
	- Se transmitirá un mensaje RQP a la dependencia ATS transferidora que originó un mensaje EST (Estimación), o al centro que originó un mensaje de actualización para el cual no se dispone de datos básicos de vuelo correspondientes.
	- Si no se ha recibido mensaje alguno, pero una aeronave establece comunicaciones radiotelefónicas y requiere los servicios de tránsito aéreo, se transmitirá un mensaje RQP a la dependencia ATS anterior a lo largo de la ruta. 
- Mensajes de solicitud de plan de vuelo suplementario.
	- RQS: Request Supplementary Information
	- Se transmitirá un mensaje RQS cuando una dependencia de los servicios de tránsito aéreo desee obtener datos de plan de vuelo suplementario.
	- Se transmitirá un mensaje RQS a la oficina de notificación de los servicios de tránsito aéreo del aeródromo de salida o, en el caso de un plan de vuelo presentado durante el vuelo, a la dependencia de los servicios de tránsito aéreo especificada en dicho mensaje de plan de vuelo.
- Mensajes de plan de vuelo suplementario.
	- SPL: Supplementary Fligth Plan Message
	- La oficina de notificación de los servicios de tránsito aéreo de aeródromo de salida transmitirá un mensaje SPL a las dependencias de los servicios de tránsito aéreo que hayan solicitado información adicional a la ya transmitida en un mensaje CPL o FPL.