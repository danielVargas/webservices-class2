Web Services - Segunda clase
==========

Ejemplo simple de cliente en base a un Web Services con protocolo REST. Para la ejecución del programa deben primer levantar el web services de Node.js (de la primera clase), luego deben compilar el código en java con el comando:

	$ javac ClienteHTTP.java

Luego para su ejecución, deberán usar el comando:

	$ java ClienteHTTP

Y el resultado que debería obtener es:

	Testing 1 - Send Http GET request

	Sending 'GET' request to URL : http://localhost:8080/tweet/1
	Response Code : 200
	{"tweet":"@maracovzla: hola! ¿como amaneciste?"}

Recuerden que deben usar la base de datos para MongoDB que viene con el proyecto de la primera clase.