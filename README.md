<a name="br1"></a> 

**TECNOLÓGICO NACIONAL DE MÉXICO**

**Instituto Tecnológico de Tláhuac**

**Desarrollo FrontEnd Web**

**Alumnos:**

Linares Pérez Margarita

**Profesor:**

Cordero Ocampo Martin

Ramon

**Grupo:**

7s2



<a name="br2"></a> 

**Contenido**

[**Resumen**](#br3)[** ](#br3)[..........................................................................................................................](#br3)[ ](#br3)[3](#br3)

[**Introducción**](#br4)[.....................................................................................................................](#br4)[ ](#br4)[4](#br4)

[**Tecnologías**](#br5)[** ](#br5)[utilizadas**](#br5)[.....................................................................................................](#br5)[ ](#br5)[5](#br5)

[**Desarrollo**](#br7)[.........................................................................................................................](#br7)[ ](#br7)[7](#br7)

[**Tabla**](#br8)[** ](#br8)[de**](#br8)[** ](#br8)[funciones**](#br8)[...........................................................................................................](#br8)[ ](#br8)[8](#br8)

[**Pruebas**](#br9)[** ](#br9)[y**](#br9)[** ](#br9)[resultados**](#br9)[.......................................................................................................](#br9)[ ](#br9)[9](#br9)

[..........................................................................................................................................](#br9)[ ](#br9)[9](#br9)

[**Conclusiones**](#br13)[.................................................................................................................](#br13)[ ](#br13)[13](#br13)

[**Bibliografía**](#br14)[.....................................................................................................................](#br14)[ ](#br14)[14](#br14)



<a name="br3"></a> 

**Resumen**

La aplicación web desarrollada con ReactJS proporciona una interfaz de usuario

intuitiva y dinámica para agregar productos a un sistema. ReactJS, una biblioteca

de JavaScript de código abierto es ampliamente utilizada en el desarrollo de

aplicaciones web por su eficiencia y capacidad para crear interfaces de usuario

interactivas.

La aplicación se compone de varios componentes modulares que trabajan juntos

para crear una experiencia fluida para el usuario. Estos componentes incluyen

formularios de entrada de datos, listas de productos, botones de acción y elementos

de navegación.

Cuando un usuario accede a la aplicación, se le presenta una interfaz limpia y bien

diseñada que le permite agregar productos fácilmente.

Una vez que se ingresan los detalles del producto y se hace clic en el botón de

"Agregar", la información se valida y se envía al sistema para su procesamiento.

ReactJS maneja de manera eficiente la actualización de la interfaz de usuario para

reflejar el estado actual de la aplicación, lo que brinda una experiencia receptiva al

usuario.

Además de agregar nuevos productos, la aplicación también permite al usuario ver

una lista de productos existentes en el sistema. Esta lista se presenta de forma clara

y ordenada, lo que facilita la búsqueda y la gestión de productos.

La aplicación web utiliza técnicas modernas de desarrollo web, como el

enrutamiento del lado del cliente, para proporcionar una experiencia de navegación

sin problemas. Esto significa que cuando el usuario interactúa con la aplicación,

como al hacer clic en un enlace de navegación, ReactJS carga y renderiza

dinámicamente el contenido correspondiente sin necesidad de recargar la página

completa.



<a name="br4"></a> 

**Introducción**

En la era digital actual, las aplicaciones web juegan un papel crucial en nuestra vida

cotidiana, desde la gestión de tareas hasta las compras en línea. La demanda de

aplicaciones web modernas y eficientes sigue en aumento, lo que ha llevado al

desarrollo de tecnologías innovadoras para satisfacer estas necesidades en

constante evolución.

Una de estas tecnologías líderes en el desarrollo de aplicaciones web es ReactJS.

ReactJS, una biblioteca de JavaScript de código abierto mantenida por Facebook

se ha convertido en la opción preferida para muchos desarrolladores debido a su

capacidad para crear interfaces de usuario interactivas y dinámicas.

En esta introducción, exploraremos el potencial de ReactJS en el desarrollo de

aplicaciones web, centrándonos en su capacidad para crear experiencias de usuario

fluidas y receptivas. Examinaremos cómo ReactJS simplifica el proceso de

desarrollo al permitir la creación de componentes reutilizables y la gestión eficiente

del estado de la aplicación.

Además, analizaremos cómo

ReactJS se integra con otras

tecnologías

y

herramientas

populares, como el enrutamiento

del lado del cliente y la gestión del

estado global, para proporcionar

una experiencia de desarrollo

completa y poderosa.

En resumen, esta introducción sienta las bases para explorar el emocionante mundo

del desarrollo de aplicaciones web utilizando ReactJS y otras tecnologías

modernas. A lo largo de este viaje, descubriremos cómo estas herramientas pueden

ayudarnos a crear aplicaciones web robustas y de alto rendimiento que satisfagan

las demandas del mundo digital de hoy en día.



<a name="br5"></a> 

**Tecnologías utilizadas**

***React JS***

React.js, comúnmente llamado simplemente React, es una biblioteca de

JavaScript que se utiliza para construir interfaces de usuario. Toda aplicación web

React se compone de componentes reutilizables que conforman partes de la interfaz

de usuario, podemos tener un componente distinto para nuestra barra de

navegación, otro para el pie de página, otro para el contenido principal, etc.

***JavaScript***

Es un lenguaje de programación o de secuencias de comandos que te permite

implementar funciones complejas en páginas web, cada vez que una página web

hace algo más que sentarse allí y mostrar información estática para que la veas,

muestra oportunas actualizaciones de contenido, mapas interactivos, animación de

Gráficos 2D/3D, desplazamiento de máquinas reproductoras de vídeo.



<a name="br6"></a> 

***CSS***

El CSS es lo que se llama un lenguaje de hojas de estilo en cascada y se utiliza

para estilizar elementos escritos en un lenguaje de marcado como HTML. Separa

el contenido de la representación visual del sitio.

CSS utiliza una sintaxis simple basada en el inglés con un conjunto de reglas

que la gobiernan. Como mencionamos anteriormente, HTML no fue hecho con

la intención de utilizar elementos de estilo, sino solo para el marcado de la

página. Fue creado simplemente para describir el contenido. Por

ejemplo**:** <p>Esto es un párrafo. </p>



<a name="br7"></a> 

**Desarrollo**

1\. Configuración del Entorno: Comienza asegurándote de tener Node.js y npm

instalados en tu sistema. Luego, crea un nuevo proyecto de React utilizando

Create React App.

2\. Crear Componentes: Define los componentes necesarios para tu aplicación.

Podrías tener componentes como Producto, Formulario, Agregar Producto, y

Enlaces a diferentes sitios web.

3\. Gestión de Estado: Utilizamos el estado de React para almacenar y

manipular la lista de productos. Se uso el hook useState para esto. Además,

necesitaremos manejar el estado de los enlaces de Facebook.

4\. Formulario de Agregar Producto: Creamos un formulario donde los usuarios

puedan ingresar detalles del producto, como nombre, precio, descripción,

etc. Al enviar el formulario, actualiza el estado de la lista de productos.

5\. Mostrar Productos: Muestra la lista de productos en tu interfaz de usuario.

Esto se realizó mapeando sobre la lista de productos y renderizando un

componente Producto para cada uno.

6\. Agregar Enlaces a Páginas de Facebook: Crea componentes o simplemente

colocamos enlaces HTML <a> que lleven a las páginas de Facebook.

7\. Estilizar la Interfaz de Usuario: Utilizamos CSS para darle estilo a la

aplicación y hacer que se vea atractiva y fácil de usar.



<a name="br8"></a> 

8\. Prueba y Depuración: Probamos la aplicación para asegurarnos de que

funcione como se espera.

9\. El testeo funciono y quedó lista.

**Tabla de funciones**

Objeto

Total

Tipo

Variable

Función

Almacenar la suma de

los productos

Datos

Arreglo de objetos

Almacena la información

de los cards para ser

creado el contenido

Componente utilizado

para crear los cards

Componente usado para

la barra de navegación

Agrega un nuevo dato en

el arreglo datos

Actualiza el componente

de cards

Actualiza la vista de los

totales

Cards

Componente

Componente

Función

Navbar

Agregarv2

Setdato

Settotal

App

Usestate

Usestate

Componente principal Componente que une

todas las funciones de la

aplicación web

*Tabla de funciones que es lo equivalente 1*



<a name="br9"></a> 

**Pruebas y resultados**

*Básicamente lo que realizamos fue una función llamada “App” que es*

*el componente principal, usamos “useState” como manejo de*

*componente local y “datos” guarda una lista de objetos con la*

*información sobre los productos.*



<a name="br10"></a> 

*Lo que se realizó fue retornar un bloque JSX que representa la estructura de la*

*barra de navegación, el elemento “nav” envuelve los elementos en barras de*

*navegación, “li” contiene enlaces para diferentes redireccionamientos sobre la*

*aplicación web.*



<a name="br11"></a> 

*Contiene los redireccionamientos a enlaces como Facebook, entre otros.*



<a name="br12"></a> 

*En esta interfaz se observan los primeros campos para ingresar a la aplicación,*

*cuenta con la caja de nombre del producto, descripción y precio del producto al*

*igual que un botón de agregar producto.*

Finalmente se tiene agregados distintos productos y quedan registrados en el

sistema.



<a name="br13"></a> 

**Conclusiones**

ReactJS simplifica la creación de interfaces de usuario mediante su enfoque basado

en componentes, lo que permite una organización clara y modular del código, la

inclusión de enlaces a páginas de Facebook muestra cómo ReactJS permite una

fácil integración de contenido externo, mejorando la experiencia del usuario y

ampliando las funcionalidades de la aplicación.

Una vez desarrollada la interfaz de usuario, se pueden realizar pruebas exhaustivas

para garantizar su funcionamiento correcto antes de proceder con el despliegue en

un servidor para su disponibilidad pública.

En resumen, esta aplicación web desarrollada en ReactJS ofrece una experiencia

de desarrollo eficiente, rendimiento optimizado y una interfaz de usuario dinámica y

atractiva, lo que la convierte en una opción popular para una amplia variedad de

proyectos web.



<a name="br14"></a> 

**Bibliografía**

*¿Qué es CSS?* (2019, January 24). Tutoriales Hostinger.

https://www.hostinger.mx/tutoriales/que-es-css

*¿Qué es JavaScript? - Aprende sobre desarrollo web | MDN*. (n.d.).

Developer.mozilla.org.

https://developer.mozilla.org/es/docs/Learn/JavaScript/First\_steps/What\_is\_

JavaScript

*¿Qué es React.js? Un Vistazo a la Popular Biblioteca de JavaScript*. (n.d.). Kinsta.

https://kinsta.com/es/base-de-conocimiento/que-es-react-js/

