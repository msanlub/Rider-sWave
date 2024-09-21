![](../img/propuesta.jpg)

## 1. IDEA

Rider`s Wave es una red social dirigida a personas que le gusten las motos.  

 Podrán agregar otros usuarios, visualizar eventos que se suban en la web a nivel nacional, hacer grupos y chatear entre los miembros del mismo para quedadas o rutas y contarán con una aplicación para el móvil por si quieren grabar las rutas y subirlas a su cuenta de la web para que otros usuarios puedan ver la ruta.  

El fin es unir, mantener una comunicación o entablar relación entre un sector cada vez más grande y disfrutar de esta afición.


## 2.AUDIENCIA

El público es muy variado y con una franja de edad muy amplia, lo que puede ser interesante para encontrar alguien con quien compartir gustos, rutas, no tener que salir sólo y por qué no… hacer amistades.   

También se contempla hacer una diferenciación entre rutas on-road y off-road, y otra sección de rodada en circuito para los más competitivos y englobar los tres sectores del mundo de las dos ruedas.


## 3.ANÁLISIS DE MERCADO

Existen varias aplicaciones móviles para moteros, y empiezan a emerger redes sociales para estos ya que ha crecido en número y en afición. 

Esta propuesta es una web accesible a todos desde su navegador, con un mantenimiento fácil y amplia escalabilidad. Cuenta con su aplicación móvil para grabar las rutas y subirlas en el perfil del usuario mediante GPS, siendo visible a sus seguidores una vez subida a su perfil para que puedan hacerla. 

En el futuro se puede ampliar a cualquier otro público (ciclismo, paddle-surf, senderismo,etc). Sólo cambiaría el diseño, la funcionalidad sería la misma.


## 4. FUNCIONALIDADES CLAVE


**Sistema de Autenticación:**
- Registro y inicio de sesión de usuarios.
- Recuperación de contraseñas y gestión de cuentas.

**Perfil de Usuario:**
- Creación y edición de perfil (nombre, foto de perfil).
- Visualización de rutas grabadas.

**Gestión de Rutas:**
- Grabación de rutas usando GPS (a través de una aplicación móvil).
- Subida y almacenamiento de rutas en el servidor.
- Visualización de rutas guardadas en el perfil del usuario.

**Redes Sociales:**
- Funcionalidad para seguir y dejar de seguir a otros usuarios.
- Visualización de las rutas y actualizaciones de los usuarios seguidos.

**Grupos y Chats:**
- Creación y gestión de grupos de moteros.
- Chat en tiempo real dentro de los grupos para coordinar salidas.

**Eventos:**
- Publicación de eventos nacionales relacionados con el motociclismo.

**Interacción Social:**
- Comentarios en rutas.
- Compartición de rutas y eventos en el perfil o en grupos.

**Mapa de Rutas:**
- Visualización de rutas en un mapa interactivo (para ver rutas grabadas).

**Notificaciones:**
- Notificaciones de nuevos mensajes en grupos.


## 5. TECNOLOGÍAS USADAS


He decidido usar JavaScript en Frontend y Backend.

- **En Frontend:**
React es una librería que ofrece muchas funcionalidades.

- **En Backend**:

 Necesito NodeJs para ejecutar JavaScript fuera del navegador, Express para desarrollarlo de manera fácil y usar diferentes librerías.

 MongoDb para mi base de datos, de la mano de Mongoose para manejarlo mejor con NodeJs.

 Heroku para despliegue de la web una vez desarrollada.

 - **En front y back**:

 React Native para desarrollar una app móvil de mi web.

 WebSocket, librería para el uso del chat de los grupos en linea sin tener que refrescar la página.

 | [Inicio](../index.md) |  [Informe técnico](./InformeTecnico.md)
