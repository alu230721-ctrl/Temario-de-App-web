# Temario-de-App-web
## Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.  

# 1.-Introducción al desarrollo web

El desarrollo web es el conjunto de actividades orientadas a la creación, diseño y mantenimiento de sitios y aplicaciones accesibles a través de Internet. Esta disciplina abarca tanto el trabajo en la parte visible para el usuario (front-end), como la gestión de datos y lógica en el servidor (back-end). Con el paso del tiempo, el desarrollo web ha evolucionado para ofrecer experiencias cada vez más interactivas, seguras y personalizadas, utilizando tecnologías como HTML, CSS, JavaScript y diversos frameworks modernos.

## Historia y evolución del desarrollo web

El origen del desarrollo web se remonta a principios de los años 90, cuando Tim Berners-Lee creó la World Wide Web y el primer navegador, junto con el lenguaje HTML. Las primeras páginas web eran estáticas y contenían solamente texto e imágenes simples. A finales de esa década, la introducción de CSS permitió separar el contenido de la presentación, mientras que JavaScript hizo posible la interacción básica en el navegador.

A medida que la web crecía, surgieron tecnologías de servidor como PHP, ASP y bases de datos que permitieron la creación de sitios dinámicos, donde el contenido podía cambiar según la interacción del usuario o los datos almacenados. Con la llegada de AJAX en los años 2000, fue posible actualizar partes de la página sin recargarla por completo, lo que dio paso a aplicaciones más rápidas y eficientes.

En la última década, el desarrollo web se ha transformado con la aparición de frameworks como React, Angular y Vue, que facilitan la creación de interfaces complejas y aplicaciones de una sola página (SPA). Además, la tendencia hacia las Progressive Web Apps (PWA) ha permitido llevar la experiencia web al nivel de las aplicaciones móviles, con funcionalidades como el trabajo offline y las notificaciones push.

## Tipos de aplicaciones web

1. **Aplicaciones web estáticas**  
   Son páginas cuyo contenido no varía y se presenta igual para todos los usuarios. Se desarrollan principalmente con HTML y CSS, y no requieren interacción con bases de datos. Ejemplos incluyen portafolios personales y sitios informativos sencillos.

2. **Aplicaciones web dinámicas**  
   Permiten que el contenido cambie en función de la interacción del usuario o los datos almacenados. Utilizan lenguajes y tecnologías del lado del servidor como PHP, Node.js o Python, junto con bases de datos. Ejemplos son blogs, tiendas online y foros.

3. **SPA (Single Page Application)**  
   Son aplicaciones que cargan una sola página HTML y actualizan el contenido dinámicamente mediante JavaScript, sin necesidad de recargar toda la página. Esto mejora la experiencia del usuario y la velocidad de navegación. Se desarrollan con frameworks como React, Angular o Vue. Ejemplos incluyen servicios como Gmail o Facebook.

4. **PWA (Progressive Web App)**  
   Son aplicaciones web que ofrecen una experiencia similar a las aplicaciones móviles nativas. Funcionan offline, pueden enviar notificaciones y se pueden instalar en dispositivos móviles. Utilizan tecnologías modernas como Service Workers para mejorar el rendimiento y la accesibilidad. Ejemplos son Twitter Lite y Spotify Web.
# Arquitectura de aplicaciones web

## 2.-Arquitectura de las aplicaciones web
La arquitectura de aplicaciones web define cómo se estructuran y organizan los componentes y servicios que permiten el funcionamiento de una aplicación en la web. Una arquitectura bien diseñada facilita el desarrollo, mantenimiento, escalabilidad y seguridad de las aplicaciones, permitiendo que los diferentes módulos interactúen de manera eficiente.

## Cliente-Servidor

El modelo Cliente-Servidor es el fundamento de la mayoría de aplicaciones web. En este modelo, el **cliente** es el dispositivo o programa (como un navegador web) que solicita recursos o servicios, mientras que el **servidor** es el sistema que procesa esas solicitudes y envía la respuesta adecuada. El cliente suele encargarse de la interfaz de usuario y la interacción, mientras que el servidor maneja el procesamiento, almacenamiento y gestión de datos.

- **Cliente:** Solicita recursos, muestra la interfaz y recibe la respuesta del servidor.
- **Servidor:** Recibe solicitudes, procesa la lógica de negocio, accede a las bases de datos y envía respuestas.

Este modelo permite separar responsabilidades y facilita la escalabilidad, ya que múltiples clientes pueden interactuar simultáneamente con uno o varios servidores.

## Arquitectura de tres capas

La arquitectura de tres capas es una evolución del modelo Cliente-Servidor, que organiza la aplicación en tres niveles distintos:

1. **Presentación:**  
   Es la capa encargada de la interacción con el usuario, normalmente implementada en el navegador o aplicación móvil. Incluye interfaces gráficas y validaciones básicas.

2. **Lógica de negocio:**  
   Es el núcleo de la aplicación, donde se procesan las reglas y operaciones principales. Aquí se toman decisiones, se procesan datos y se gestiona el flujo de la aplicación.

3. **Datos:**  
   Es la capa responsable del almacenamiento y recuperación de información, típicamente a través de bases de datos. Se encarga de guardar, modificar y consultar los datos de la aplicación.

Esta separación permite que cada capa se desarrolle y mantenga de forma independiente, mejorando la organización, la seguridad y la escalabilidad del sistema.

## REST y API-first design

### REST (Representational State Transfer)

REST es un estilo de arquitectura para el diseño de servicios web, donde los recursos se exponen a través de URLs y se manipulan usando los métodos estándar de HTTP (GET, POST, PUT, DELETE, etc.). Las aplicaciones basadas en REST son fáciles de escalar, mantener y consumir, ya que siguen convenciones claras y utilizan formatos de datos ligeros como JSON o XML.

**Principios de REST:**
- Uso de HTTP y sus métodos.
- Recursos identificados por URLs.
- Intercambio de datos sin estado (stateless).
- Representaciones de recursos en formatos estándar.

### API-first design

El enfoque API-first consiste en diseñar la API antes que el resto de la aplicación, estableciendo las reglas y contratos de comunicación entre componentes desde el principio. Este método es ideal para aplicaciones que requieren integración entre múltiples servicios o dispositivos (front-end, back-end y terceros), ya que asegura que todos los equipos trabajen sobre un mismo estándar y facilita la escalabilidad y el mantenimiento.

**Ventajas del API-first design:**
- Alineación entre equipos de desarrollo.
- Documentación clara y reutilizable.
- Facilita el desarrollo paralelo de front-end y back-end.
- Mejora la integración y la interoperabilidad.

# 3.-Lenguajes y tecnologías fundamentales

El desarrollo web se basa en diversos lenguajes y tecnologías que permiten crear interfaces atractivas, interactivas y funcionales, así como gestionar la lógica y los datos en el servidor. A continuación se describen los principales lenguajes y tecnologías fundamentales:

## HTML (HyperText Markup Language)

HTML es el lenguaje de marcado principal para la creación de páginas web. Define la estructura y el contenido básico de un sitio, como títulos, párrafos, listas, imágenes, enlaces y formularios. Los navegadores web interpretan el código HTML para mostrar la información al usuario.

**Características principales:**
- Define la estructura de la web.
- Utiliza etiquetas como `<html>`, `<head>`, `<body>`, `<h1>`, `<p>`, etc.
- Es la base sobre la que se aplican estilos y scripts.

## CSS (Cascading Style Sheets)

CSS es el lenguaje utilizado para controlar la apariencia y el diseño de los elementos HTML. Permite definir colores, fuentes, márgenes, posiciones, animaciones y estilos responsivos. Gracias a CSS, las páginas web pueden adaptarse a diferentes dispositivos y ofrecer una experiencia visual agradable.

**Características principales:**
- Separa el contenido de la presentación.
- Permite crear diseños adaptativos (responsive).
- Utiliza selectores y reglas para aplicar estilos.

## JavaScript

JavaScript es el lenguaje de programación fundamental para agregar interactividad y dinamismo a las páginas web. Se ejecuta en el navegador, permitiendo responder a eventos del usuario, modificar el contenido de la página en tiempo real y comunicar con el servidor sin recargar la página (AJAX).

**Características principales:**
- Permite manipular el DOM (estructura de la página).
- Implementa lógica en el lado del cliente.
- Es la base de frameworks y librerías modernas (React, Angular, Vue).

## PHP

PHP es un lenguaje de programación que se ejecuta en el servidor y se utiliza principalmente para construir aplicaciones web dinámicas. Permite procesar formularios, gestionar sesiones, interactuar con bases de datos y generar contenido HTML personalizado para cada usuario.

**Características principales:**
- Se ejecuta en el servidor.
- Facilita la creación de páginas dinámicas.
- Amplia integración con bases de datos (especialmente MySQL).

## MySQL

MySQL es un sistema de gestión de bases de datos relacional muy utilizado en el desarrollo web. Permite almacenar, organizar y recuperar grandes volúmenes de datos de manera eficiente. Es comúnmente usado junto con PHP para construir aplicaciones que requieren persistencia de información, como blogs, tiendas en línea y sistemas de usuarios.

**Características principales:**
- Almacena y organiza información en tablas.
- Permite consultas complejas mediante el lenguaje SQL.
- Es gratuito, robusto y ampliamente soportado. 

# 4.-Control de versiones

El control de versiones es una práctica fundamental en el desarrollo de software que permite registrar, supervisar y gestionar los cambios realizados en el código fuente de un proyecto a lo largo del tiempo. Gracias al control de versiones, los desarrolladores pueden colaborar de manera eficiente, recuperar versiones anteriores y mantener la integridad del código.

## Git y GitHub

**Git** es un sistema de control de versiones distribuido, creado por Linus Torvalds, que facilita el seguimiento de los cambios en archivos y la coordinación entre equipos de desarrollo. Permite trabajar de manera local y remota, brindando gran flexibilidad y seguridad para proyectos pequeños y grandes.

**GitHub** es una plataforma en línea que utiliza Git como base, pero añade funcionalidades colaborativas como la gestión de repositorios, seguimiento de problemas (issues), revisión de código y documentación. GitHub facilita el trabajo en equipo, la publicación de proyectos y la colaboración con desarrolladores de todo el mundo.

## Flujo de trabajo con ramas (branching, merge, pull requests)

Un flujo de trabajo común en proyectos modernos consiste en aprovechar las **ramas** de Git para desarrollar nuevas funcionalidades, corregir errores o experimentar sin afectar el código principal. El proceso general es:

1. **Branching (creación de ramas):**  
   Se crea una nueva rama a partir de la principal (generalmente llamada `main` o `master`). En esta rama se realizan todos los cambios relacionados con una nueva funcionalidad o corrección.

2. **Merge (fusión de ramas):**  
   Una vez que los cambios en la rama están listos y probados, se integran (fusionan) con la rama principal. Git ayuda a resolver posibles conflictos surgidos de cambios simultáneos en el código.

3. **Pull Requests:**  
   En plataformas como GitHub, antes de fusionar una rama, se realiza un "pull request", que es una solicitud para revisar y aprobar los cambios antes de integrarlos al proyecto principal. Los revisores pueden comentar, proponer mejoras y aprobar o rechazar los cambios. Este proceso fomenta la colaboración, la calidad del código y la transparencia.

<img width="309" height="143" alt="image" src="https://github.com/user-attachments/assets/605a3f6b-7970-477f-b929-b04fde817d08" />


## Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web  

# 1. Diseño e implementación del frontend

El **frontend** es la parte de la aplicación web con la que interactúan directamente los usuarios. Su diseño y desarrollo implica crear interfaces visuales atractivas, funcionales y accesibles.

- **Maquetación, Wireframe y Mockup:**  
  La maquetación consiste en organizar los elementos visuales de una página (texto, imágenes, botones, menús, etc.) usando herramientas como HTML y CSS. Antes de programar, se suelen crear wireframes (esquemas simples) y mockups (diseños detallados) para planificar la estructura y el aspecto visual.
- **API:**  
  El frontend suele comunicarse con el backend a través de APIs (Interfaces de Programación de Aplicaciones), obteniendo y enviando datos para actualizar la interfaz dinámicamente.

---

# 2. Diseño e implementación del backend

El **backend** es la parte de la aplicación que gestiona la lógica, el procesamiento de datos y la comunicación con la base de datos. No es visible para el usuario, pero es fundamental para el funcionamiento de la aplicación.

- **Servidor:**  
  El backend se ejecuta en un servidor, que recibe las peticiones del frontend y responde según la lógica de la aplicación.
- **Manejo de peticiones y respuestas HTTP:**  
  El backend procesa las solicitudes HTTP (GET, POST, PUT, DELETE, etc.) que llegan desde el cliente, ejecuta las operaciones necesarias y devuelve respuestas (generalmente en formato JSON).
- **Conexión a bases de datos (MySQL, PostgreSQL, MongoDB):**  
  El servidor se conecta a bases de datos para almacenar, consultar y modificar información. MySQL y PostgreSQL son sistemas relacionales, mientras que MongoDB es una base de datos NoSQL orientada a documentos.

---

# 3. Bases de datos

Las bases de datos permiten almacenar y organizar información de manera eficiente y segura.

- **Modelado de datos y relaciones:**  
  Consiste en definir cómo se estructuran los datos y las relaciones entre ellos (por ejemplo, usuarios y sus pedidos). En bases de datos relacionales, esto se realiza mediante tablas y claves foráneas.
- **ORM (Object Relational Mapping):**  
  Los ORM son herramientas que facilitan la interacción entre el código del backend y la base de datos, permitiendo trabajar con objetos en el lenguaje de programación en vez de escribir consultas SQL directamente (ejemplos: SQLAlchemy, Sequelize, Doctrine).
- **CRUD desde el backend:**  
  El backend implementa las operaciones básicas sobre los datos: Crear (Create), Leer (Read), Actualizar (Update) y Borrar (Delete), conocidas como CRUD.

---

# 4. Seguridad básica en aplicaciones web

La seguridad es esencial para proteger la información y a los usuarios de una aplicación.

- **Validación de formularios:**  
  Consiste en revisar los datos que ingresan los usuarios para evitar errores y ataques (por ejemplo, SQL Injection), comprobando que los campos sean correctos antes de procesarlos.
- **Autenticación y autorización:**  
  La autenticación verifica la identidad del usuario (por ejemplo, mediante usuario y contraseña), mientras que la autorización determina qué acciones puede realizar ese usuario dentro de la aplicación. Implementar estas medidas ayuda a proteger datos sensibles y restringir el acceso a funcionalidades según los permisos.

<img width="299" height="168" alt="image" src="https://github.com/user-attachments/assets/5428ee76-aea8-4b5c-8f86-833e9704a971" />


# Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional  
# 1. Integración de frontend y backend

La integración entre frontend y backend es fundamental para crear aplicaciones web completas y funcionales. Este proceso permite que la **interfaz de usuario** (frontend), diseñada para la interacción del usuario, se comunique con la lógica y los datos gestionados por el **backend**.

- **Interfaz de usuario Frontend:**  
  El frontend proporciona la estructura visual y la experiencia de usuario, enviando solicitudes (como formularios o clics) al backend para obtener o modificar información.

- **Manejo de API:**  
  La integración se realiza mediante APIs (Application Programming Interfaces), que definen los métodos y rutas para que el frontend solicite datos al backend y reciba respuestas estructuradas (usualmente en formato JSON).

- **Proceso de Solicitud y Respuesta de Backend:**  
  El frontend envía solicitudes HTTP (GET, POST, PUT, DELETE) al backend, que procesa la petición, consulta la base de datos si es necesario y responde al frontend con los datos solicitados o el resultado de una operación.

---

# 2. Almacenamiento en Servidor

El almacenamiento en el servidor es esencial para guardar archivos, datos y recursos necesarios para el funcionamiento de la aplicación web.

- **Tipos de servidores:**  
  Los servidores pueden ser dedicados (exclusivos para un cliente), virtuales (VPS), compartidos (varios usuarios en un mismo servidor físico) o servidores en la nube, que ofrecen escalabilidad y flexibilidad.

- **Servidores y servicios de hosting:**  
  El hosting es el servicio que permite publicar aplicaciones web en Internet. Puede ser tradicional (servidores físicos o virtuales) o en la nube, con proveedores como AWS, Azure, Google Cloud, Heroku, entre otros.

- **Proveedores de Servicios de Almacenamiento:**  
  Existen servicios especializados en almacenamiento de archivos y datos, como Amazon S3, Google Cloud Storage y Dropbox, que facilitan el manejo de grandes volúmenes de información, respaldo y recuperación ante fallos.

---

# 3. Optimización y rendimiento

La optimización y el rendimiento son claves para ofrecer una experiencia rápida y eficiente a los usuarios.

- **Optimización de recursos (imágenes, scripts):**  
  Consiste en reducir el tamaño de imágenes, minificar scripts y hojas de estilo, y utilizar técnicas como lazy loading para cargar recursos solo cuando son necesarios.

- **Despliegue de aplicaciones web:**  
  El despliegue implica publicar la aplicación en un servidor o servicio de hosting, asegurando que esté disponible para los usuarios. Incluye la configuración de dominios, certificados SSL y la automatización de tareas de actualización.

- **CI/CD básico (Integración y Entrega Continua):**  
  CI/CD son prácticas para automatizar la integración, pruebas y despliegue del código. Herramientas como GitHub Actions, Jenkins y GitLab CI permiten que los cambios en el código se prueben y publiquen automáticamente, reduciendo errores y acelerando el desarrollo.

- **Documentación del proyecto:**  
  La documentación clara y accesible facilita la comprensión, mantenimiento y colaboración en el proyecto. Incluye guías de instalación, uso, arquitectura y referencias de API, y puede elaborarse en archivos Markdown, wikis o portales especializados.
