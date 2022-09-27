### 3. Analiza los headers de las peticiones cuando inicias sesión en el Moodle y comprende
### cómo se obtiene el token. Para ello, necesitamos saber de dónde salen TODOS los
### datos sensibles que se envían.
![image](https://user-images.githubusercontent.com/113515441/192512769-4d307c08-82b6-4935-ad4f-4cede814aee1.png)
![image](https://user-images.githubusercontent.com/113515441/192512834-68ac5ef7-a63a-4e99-ac8b-f665a8be10b3.png)



El token se obtiene usando una API

### 4. ¿A qué puerto se reciben normalmente las peticiones del protocolo HTTP? ¿A qué
### capa del modelo TCP/IP se encuentra el protocolo HTTP? ¿Y los protocolos TCP,
### UDP, e IP?
-Es el puerto 80. Se pueden usar otros puertos como el 8000 o el 8080.
-Capa 4 o de aplicación
-Capa 3 o de transporte

### 5 ¿Cuál es el significado de la siguiente respuesta de un servidor?
### HTTP/1.1 302 Found
### Location: http://www.example.com/test/index2.php 
El recurso solicitado ha sido movido temporalmente a la URL dada por las cabeceras Location 

### 6. Utilizando el filtro de captura para la interfaz de red de Wireshark, analiza la petición
### al host: www.google.com. Mostrando la cabecera IP, la dirección IP de tu ordenador y
### la del servidor. Comprueba que, poniendo esa IP en el navegador, accedas a Google.

![image](https://user-images.githubusercontent.com/113515441/192511255-de623238-574e-487f-aeac-a9f2db3307b1.png)
![image](https://user-images.githubusercontent.com/113515441/192511345-085fe6d1-8c8f-4fe7-bde4-a429defade6c.png)
![image](https://user-images.githubusercontent.com/113515441/192511395-b3bfaf4c-ac66-40a1-a4ae-b944bcb4e6e8.png)


