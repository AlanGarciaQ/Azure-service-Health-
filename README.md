# Azure service Health 
**Objetivo:** Conocer el funcionamiento del recurso de Azure Service Health.   

![](/imagenes/virtual%20machine.png)

**Requisitos**
- Cuenta de Azure con una suscripción activa.
- Equipo de cómputo con sistema operativo: Windows, Linux o MacOs. 

**Pasos**  
Se inicia sesión en Portal.Azure.com  
En la barra de búsqueda escribimos “Service Health” y lo seleccionamos.  
Damos clic en añadir una alerta de service Health.  
En el apartado de servicios seleccionamos el servicio o servicios que queremos que este checando por si fallan estos.  
En región podemos poner que sea global o en regiones específicas.  
En tipo de evento el tipo de problema que queremos que nos notifique.  
Damos clic en seleccionar grupos de acciones.  
Damos clic en crear grupo de acciones.  
![Imagen 1](/imagenes/Imagen1.png)

En la pestaña datos básicos, llenamos lo siguiente:

**En Detalles del proyecto**  
Suscripción: La suscripción que queramos utilizar.  
Grupo de recursos: Podemos crear uno o seleccionar uno ya existente.

**En Detalles de Instancia**  
Nombre del grupo de acciones: Ponemos el que queramos.  
Nombre para mostrar: Podemos dejar el que se creó o escribir uno.

Damos clic en el botón de siguiente: Notificaciones.  
![](/imagenes/Imagen2.png)

En Notificaciones, llenamos lo siguiente:  
Tipo de notificación: Seleccionamos el medio por le que recibiremos las notificaciones.  
Nombre: Ponemos el nombre que queramos que tenga nuestra notificación.

En la ventana que nos apareció a la derecha colocamos la información nuestra por la que queremos que nos envíen la notificación. Al terminar le damos en aceptar.  
Por último, damos clic en el botón de revisar y crear.  
Damos clic en el botón de grupo de acciones de prueba.  
Damos clic en crear.
![](/imagenes/Imagen3.png)

Seleccionamos el grupo de acciones que hicimos.  
Seleccionamos la opción de grupo de acciones de prueba.  
En seleccionar el tipo de ejemplo seleccionamos el que queramos y le damos clic en test.  
Nos debería enviar a nuestro correo una notificación.  
![](/imagenes/Imagen4.png)

La notificación de prueba de Azure en nuestro correo electrónico que escribimos para recibir notificaciones.  
![](/imagenes/Imagen5.png)

Damos clic en la X de la parte superior derecha para salir de esa ventana.  
En la ventana de crear una regla de alertas crearemos una regla de alertas.  
Pondremos el nombre de la alerta, una descripción y seleccionamos un grupo de recursos.  
Damos clic en crear regla de alertas.  
![](/imagenes/Imagen6.png)

Así creamos dos recursos, un grupo de acciones y una regla de alertas por si paso algo en los servicios de Azure.  
![](/imagenes/Imagen7.png)

