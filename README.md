# Laboratorio 4
---
## Descripcion de la aplicacion

Una aplicacion que le permita al usuario poder registrarse con un usuario y contraseña, que almacene su telefono y se conecte con los contactos ya registrados que tenga en su dispositivo. En esta app, el usuario seleccionará una pestaña, la cual almacenará los contactos del telefono que esten registrados en la app. En esta pestaña, se abrira una interfaz en la que puede escribir de manera directa con otro usuario. Al momento de seleccionar un usuario para generar una conversacion, esta se almacena directamente en la interfaz de "conversaciones" la cual se van ordenando los chats de manera cronologica desde el mas reciente al menos reciente.
El usuario, al momento de ingresar el chat, puede comenzar la conversacion mediante audio o escritura con el otro usuario donde se ira almacenando cada mensaje con su respectiva fecha y hora. Los mensajes se iran mostrando a modo de scroll, donde en la parte derecha se veran los mensajes del emisor y al lado izquierdo los mensajes del destinatario. Estos mensajes quedaran registrados en dicha interfaz, generando un historial con todos los mensajes de ambos usuarios en esa conversacion. 
El usuario puede realizar la generacion de la conversacion con cualquiera de los contactos a los que tenga agregado, donde automaticamente se hará la conexion mediante el chat y el otro usuario recibira una notificacion de que alguien esta intentando comunicarse con él. Este usuario, tendra el mensaje y el chat a disposicion y visualizacion directa, en la cual puede optar a responder o no responder. Por otra parte el usuario puede bloquear a cualquier contacto de su lista.
Al ser una aplicacion que se centra exclusivamente en la comunicacion rapida, sencilla y eficaz con un contacto, no es necesaria una aprobacion previa para recibir un mensaje o la necesidad de "agregar" como amigo a los contactos, debido a que se conecta automaticamente a los contactos propios que ya esten registrados en la plataforma. Sumado a lo anterior, al ser una plataforma de comunicacion rapida, no existe la eliminacion ni edición de mensajeria.

---

## Historia 1
**Como** usuario registrado
**quiero** poder visualizar la lista de todos los usuarios dentro de mis contactos que esten registrados en la plataforma
**para que** pueda observar a quien puedo contactar mediante la aplicacion

### Objetivo principal
Permitir al usuario poder visualizar y revisar todos aquellos contactos propios que esten registrados en la app y que tenga agregado en su telefono, donde se ordenarán de manera alfabetica a modo de scroll los contactos mediante el nombre que el usuario los tenga agregados anteriormente desde su telefono. Con esto podra tener el conocimiento sobre con que contactos suyos puede comunicarse de manera directa por la app.

### Criterios de aceptacion
-Visualizacion de contactos registrados ordenados alfabeticamente

-Scroll en la lista

-Visualizacion de contactos segun se hayan registrado en el telefono por el usuario

---

## Historia 2
***Como*** usuario registrado
***quiero*** enviar mediante mensaje de texto una invitacion a mis contactos no registrados en la app
***para que*** puedan descargarla y utilizarla

### Objetivo principal 
Permitir al usuario registrado enviar un mensaje de texto a los contactos que no tengan y no esten registrados en la app 

### Criterios de aceptacion
-Lista de contactos que no esten registrados en la app

-Boton para enviar mensaje de texto por contacto con la leyenda "Descarga la siguiente app de mensajeria"

-checkbox para seleccionar contactos y enviar el mensaje "Descarga la siguiente app de mensajeria" de manera masiva

-Mensaje de enviado exitosamente para envío de mensaje para un contacto o de manera masiva

---

## Historia 3

***Como*** usuario registrado
***quiero*** recibir una notificacion push en mi celular, donde me muestre el nombre de la persona, la hora y el mensaje
***para*** poder ver el mensaje sin necesidad de abrir el chat

### Objetivo principal
Permitir al usuario recibir una notificacion audible y visible, que contenga un sonido especial, un icono representativo y un banner flotante en el panel de notificaciones el cual indique nombre, mensaje y hora que fue recibido

### Criterios de aceptacion
-sonido especial al momento de recibir una notificacion de la app

-icono especial al momento de recibir una notificacion de la app

-banner flotante en el panel de notificaciones que contemple el nombre, la hora y el mensaje

---

## Historia 4

***Como*** usuario registrado
***quiero*** visualizar la lista de chats, que esten ordenados por interacción, de la mas reciente a la mas antigua,
***para*** ver de manera facil, rapida y ordenada mis chats con mis contactos

### Objetivo principal
Permitir al usuario visualizar la lista de chats a modo de scroll, de la mas reciente a la mas antigua, donde se muestren sus diferentes conversaciones, que incluya nombre de la persona, hora y ultimo mensaje. 

### Criterios de aceptacion
-ordenar los chats cronologicamente, del mas reciente al mas antiguo

-lista de chats con scroll

-tarjeta con nombre de usuario, hora y ultimo mensaje

---

## Historia 5

***Como*** usuario registrado
***quiero*** ingresar a la plataforma por medio de un login donde pueda ingresar mi usuario y contraseña
***para*** tener mayor seguridad al ingresar a mis chats

### Objetivo principal
Permitir al usuario ingresar por medio de un login a la plataforma, que solicite un usuario y contraseña, y posteriormente se diriga a la interfaz de chats.

### Criterios de aceptacion
-cuadro de texto de usuario, cuadro de texto de contraseña con boton para poder esconder o visualizar contraseña registrada

-boton para login

-mensaje de error si usuario no esta registrado

-mensaje de error si registro mal usuario y/o contraseña

---

## Historia 6

***Como*** usuario registrado
***quiero*** enviar un mensaje a otro usuario registrado
***para*** iniciar y mantener una conversacion

### Objetivo principal
Permitir al usuario acceder a una ventana de chat, seleccionando a un usuario registrado. Por medio de un boton y un cuadro de texto se podrán enviar mensajes, diferenciando al emisor como al receptor con colores diferentes.

### Criterios de aceptacion
-ventana de chat

-boton para enviar mensaje 

-cuadro de texto para escribir mensaje

-diferenciación de color; emisor y receptor

---

## Historia 7

***Como*** usuario registrado
***quiero*** leer el historial de mensajes con otro usuario en una vista de mensajes dedicada
***para*** tener un registro de la conversacion

### Objetivo principal
Permitir al usuario acceder a una vista de mensajes dedicada dentro del chat, mostrando el historial de conversacion y que pueda hacer scroll

### Criterios de aceptacion
-hacer scroll

-ordenar cronologicamente la conversacion

---

## Historia 8

***Como*** usuario registrado
***quiero*** bloquear un contacto de mi lista 
***para*** no volver a contactarme con él

### Objetivo principal
Permitir al usuario bloquear a cualquier contacto de su lista de chats mediante un boton y notificar unicamente a él, que el contacto a sido bloqueado, dando la opcion mediante el mismo boton para desbloquearlo

### Criterios de aceptacion
-boton para bloquear

-cuadro de texto con mensaje de "usuario bloqueado"

-cuadro de texto con mensaje de "usuario desbloqueado"

---

## Historia 9

***Como*** usuario registrado
***quiero*** enviar audios a traves de la conversacion manteniendo presionado un boton con la figura de un microfono, 
***para*** contactarme mediante voz 

### Objetivo principal
Permitir al usuario mediante un boton con una icono de microfono, el cual estara en el costado derecho del cuadro de texto, realizar una grabacion y enviar 

### Criterios de aceptacion
-boton para enviar audio

-tarjeta con reproductor de audio

-boton para reproducir audio

---

## Historia 10

***Como*** usuario registrado
***quiero*** un buscador donde pueda buscar por nombre un respectivo chat
***para*** acceder de manera mas facil y rapida a un contacto

### Objetivo principal
Permitir al usuario mediante un cuadro de texto y boton de busqueda en la parte superior de la interfaz de conversaciones, que pueda filtrar de manera cronologica de la mas reciente a la mas antigua, por nombre, y así buscar de manera rapida y sencilla cualquier contacto

### Criterios de aceptacion
-cuadro de texto de busqueda

-boton para realizar busqueda 

-ordenar los nombres y chat de manera cronologica  

---
