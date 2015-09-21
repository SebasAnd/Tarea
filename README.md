# Tarea Redes

Andres Cortes - 1332345  
Jhonatan Noguera - 1329700   

### Metodo de ejecución Sockets

Para ejecutar los siguientes programas es necesario usar la consola del sistema. y colocar el comando   
``python nombredelarchivo.py`` 

### Archivos en Sockets

- socket-02.py: Almacena la IP dado un nombre de servidor en nuestra variable remote_ip. Para imprimirla en pantalla posteriormente  

- socket-03.py: Extension de socket-02.py, conecta un socket y se imprimer en pantalla el nombre del host y su ip  

- socket-04.py: Extension de socket-03.py, envia un mensaje al servidor en que esta conectado  

- socket-05.py: Extension de socket-04.py, imprimer en pantalla la respuesta del servidor

### Metodo de ejecución Cliente-Servidor

Para ejecutar los siguientes programas es necesario usar la consola del sistema. y colocar el comando   
``python nombredelarchivo.py --port NrodePuerto`` 

Tener en cuenta de primero ejecutar el servidor antes que el cliente.

### Archivos en Cliente-Servidor

- echo-server.py: Crea un servidor, recibe un puerto y en dicho puerto crea el servidor para establecer una conexion con el cliente que enviara mensajes

- echo-client.py: Crea un cliente para conectarse con el servidor creado por echo-server y enviar mensajes a estes. Es impportante que el puerto de creacion del cliente sea igual al puerto donde se creó el servidor
