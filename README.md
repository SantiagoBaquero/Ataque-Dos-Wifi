# Pasos a seguir para la ejecucion del laboratorio DoS
1. En la maquina de linux ejecutar el siguiente comando:  *iwconfig*
   
    Te mostrala la wlan0 de tu equipo esta debe estar en Mode: manage
   
2.  Ejecuamos el siguiente comando: *nano wifidos.py*

   
       Dentro de este archivo *wifidos.py* copiamos el contenido de cualquiera de los dos archivos DOS_TYPE.PY o DOS_TYPE2.PY posterior <Clt+x> - Y , estaria listo el archivo.

3. Ejecutaremos el script escribimos: *sudo python3 wifidos.py*


     Este nos solicita que seleccionemos la interfaz Wi-fi a atacar selecionamos la interfaz correspondiente ejemplo: 0
esto hace que pase la interfaz de modo manage a modo monitoreo, nos mostrara todas las redes wifi que detecta alrededor.

Buscamos  el equipo en el cual estamos realizando este laboratorio ejemplo la opcion (8) introducimos ese valor (8) esto ocasionara la DeAuth de los dispositivos.

4. Este tambien nos genera detalles de los dispositivos que se DeAuth


     *cd backup* - Encontraremos el archivo o archivos generados cada que se realiza la ejecucion.


    *cat (nombre archivo)* - Podremos visualizar el contenido del mismo.
   
**Esto se debe realizar unicamente en ambientes controlados y con autorizacion de los implicados, no me hago responsable del uso de esta informacion la cual es compartida de forma academica unicamente.**


### Script obtenidos de David Bombal muchas gracias. https://github.com/davidbombal/red-python-scripts





    
