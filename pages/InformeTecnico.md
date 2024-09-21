![](./img/informeTecnico.jpg)

## 1. MODELO EJECUCIÓN CLIENTE/SERVIDOR

### **Ejecución en cliente**

Toda la parte de maquetado, estilo y funcionalidades de usuario se desarrollan en cliente.  El código es ejecutado en el mismo navegador (HTML5, CSS y JavaScript), y se crean aplicaciones dinámicas para el usuario sin necesidad de refrescar la página.

### **Ejecución en servidor**

Se encarga del almacenamiento de datos y procesarlos de manera segura (sin que los usuarios tengan acceso a ellos) y enviar la información solicitada al cliente. Se ejecuta en el servidor web configurado y para ello existen muchos lenguajes como PHP, Python y tecnologías como Node.js, MongoDb para gestionar nuestra base de datos y nuestro servidor.

### **Ejemplo de uso en aplicación motera:**

En **cliente**(navegador) se ejecuta todo lo que sea interfaz, lógica del chat, subida de eventos, agregar usuarios, crear grupos..

El **servidor** se encargaría de almacenamiento de datos y mensajes, verificar usuarios, cargar las rutas, sincronizar los mensajes de chat..

### **Ejemplos de uso en otras aplicaciones:**


|         EJEMPLO         |                                 CLIENTE                                       |                                 SERVIDOR                                   |
|-------------------------|-------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| **Whatsapp web**            | La interfaz y la lógica de mensajes se manejan en el navegador                | Se encarga de la sincronización y el almacenamiento de mensajes           |
| **Juegos de Navegador**     | Se ejecutan en el navegador del cliente, usando JavaScript para renderizar gráficos y manejar la lógica del juego en tiempo real | Sincroniza el estado del juego entre jugadores                           |
| **YouTube**                 | La reproducción de videos se maneja en el navegador del usuario, usando HTML5 y JavaScript para controlar la reproducción, el volumen y la calidad del video | Carga los datos de los videos                                            |
| **Google Maps**             | La interacción con el mapa, como el desplazamiento, el zoom y la búsqueda de ubicaciones, se maneja en el navegador del cliente | Carga los datos del mapa y las rutas                                     |
| **Canva**                   | La interfaz de edición, los controles y la vista previa de los diseños se manejan en el navegador | Almacena los archivos                                                   |
| **Tienda online**           | Los usuarios pueden personalizar productos (como elegir colores, accesorios, etc.) en tiempo real en su navegador, con actualizaciones visuales, filtrado y búsqueda | Maneja el almacenamiento de configuraciones, gestión del inventario y procesamiento de pagos |





## 2. EVALUACIÓN DE LOS LENGUAJES DE PROGRAMACIÓN 


Hay muchos lenguajes que se usan para el front como JavaScript, TypeScript, Elm, Dart (también puede ser compilado en .js), pero nos vamos a centrar en los dos primeros ya que son los más usados y los que cuentan con más bibliotecas y funcionalidades.

Ambos lenguajes son muy parecidos, aunque TypeScript es más robusto y seguro, con fuerte tipado, uso de interfaces y mejor preparado para POO que JavaScript. Es un lenguaje más maduro pero tiene una curva de aprendizaje más elevada. Hay que tener en cuenta que debe ser transpilado a .js para ejecutar en navegador, lo cuál viene bien para evitar errores en tiempo de ejecución, pero el proceso lo puede hacer algo más complicado.
Todo el código escrito en JavaScript puede ser usado en TypeScript pero no al revés. TypeScript se le considera un superconjunto sintáctico de JavaScript.

Para este proyecto he decidido usar JavaScript, por la facilidad que puede aportar, por las muchas bibliotecas que se pueden usar y tecnologías, y por la amplia compatibilidad con navegadores.

## 3. COMPATIBILIDAD EN NAVEGADORES

Hay variaciones en cómo cada navegador maneja ciertos elementos, sobre todo con las nuevas funcionalidades de JavaScript. Esto se debe a que algunos navegadores antiguos o no actualizados no soportan las actualizaciones de especificación de JavaScript (ECMAScript). Para ello se puede usar herramientas como Babel, que es un transpilador que convierte el código moderno de JavaScript a una versión más compatible o Polyfills para cubrir funcionalidades que navegadores antiguos no sean capaz de “entender”.

Estos problemas de compatibilidad lo encontramos también en CSS, con funcionalidades como grid o flexbox, que son utilidades nuevas y los navegadores antiguos no estan implementados. Incluso algunos eventos y métodos de manipulación del DOM funcionan diferentes en navegadores antiguos.

De todas formas, los navegadores más usados como Chrome, Firefox, Safari u Opera si están actualizados y son compatibles con la mayoría de funcionalidades nuevas y se seguirán actualizando. Personalmente no creo que haya muchos usuarios que se salgan de ese marco de navegadores.

## 4. INTEGRACIÓN DE LENGUAJE DE MARCA Y DE PROGRAMACIÓN

Partiendo de la base de que HTML sirve para crear la estructura de una página web, CSS para darle estilo y JavaScript para aportar funcionalidad y dinamismo, cuando el navegador abre el HTML crea un documento(DOM) en el que se guarda la estructura en árbol que refleja la jerarquía del contenido del HTML.

 El DOM(Document Object Model) permite que tanto los estilos (CSS) como la funcionalidad dinámica (JavaScript) se apliquen y modifiquen la estructura y el contenido de la página. 

En el head del HTML, donde se encuentran los metadatos de la página, se enlaza el código de CSS y el script de JavaScript.

Es el conjunto de los tres lenguajes el que construye webs dinámicas y con un diseño atractivo para el usuario.

## 5. HERRAMIENTAS DE PROGRAMACIÓN WEB

 **Edición de código:**

 Voy a usar Visual Studio Code, un IDE fácil para trabajar y con extensiones que pueden ayudar a ver errores más claros en el código (autocompletado, debug, análisis de código..). 
 
 Además es compatible con muchos lenguajes de programación, bibliotecas, frameworks y trabaja con control de versiones Git. Ofrece mucha flexibilidad para personalizarlo según el proyecto o lenguajes usados.

 **Frameworks y bibliotecas pensadas para el proyecto:**

- **NodeJs** -> entorno de ejecución para usar JavaScript tanto para cliente como para servidor, dando la posibilidad de ejecutar JavaScript fuera del navegador.  Cuenta con muchas utilidades para una amplia gama de uso, lo cual es perfecto para la red social.

- **Express** -> framework o entorno   para trabajar con NodeJs.

- **WebSocket** -> biblioteca para la conexión en linea del chat sin tener que refrescar la página (aplicado tanto en cliente como en servidor).

- **React** -> Biblioteca de JavaScript para crear la interfaz interactiva(cliente).

- **MongoDb** -> Para una base de datos de fácil escalabilidad y rápida, ya que vamos a almacenar datos flexibles (las rutas,los perfiles de usuario,eventos…)(servidor)

- **Mongoose** -> Librería para manejar mejor mi base de datos en MongoDb con Node(servidor).

- **React Native WebView** -> framework para crear la aplicación móvil(PWA) que pueda acceder al GPS para grabar las rutas y subirlas al servidor a partir de mi aplicación móvil. Una Progressive Web App (PWA) es crear la aplicación móvil para web, ejecutándose en navegador pero pudiendo descargarla como una aplicación móvil.

- **Heroku** -> Para desplegar fácilmente aplicaciones Node.js. Ambas plataformas son populares y fáciles de usar para proyectos pequeños y medianos.


## 6. ANÁLISIS DE MERCADO

Existen muchas aplicaciones para móvil donde te guian para no coger atascos, o aplicaciones que te ayudan con el mantenimiento de la moto, o incluso aplicaciones móviles que puedes llevar en circuito y te dan valores de velocidad, inclinación, aceleración para mejorar en competición.

También existen muchos foros webs de moteros, donde exponen eventos o se debate sobre qué escape es mejor para qué moto.

Esta web con aplicación móvil engloba todo para poder crear una unión entre riders y mantener el contacto para cada salida y ruta que quieran compartir.

Cualquier afición es mejor si tenemos con quién compatirlas.


 | [Inicio](./index.md) |  [Propuesta](./pages/Propuesta.md)
