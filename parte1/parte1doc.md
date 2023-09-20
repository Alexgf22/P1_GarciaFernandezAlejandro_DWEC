# Parte 1 - Modelos de Programación en Entornos Cliente/Servidor

## Indice

    1. Investigación de los modelos cliente/servidor más comunes.
        * Algunos de los modelos de arquitectura web más comunes
            1. Arquitectura de SPA (Single Page Application)
            2. Arquitectura de Progresive Web Apps (PWA)
            3. Cliente/Servidor

    2. Identificación de ejemplos de aplicaciones que utilizan cada modelo.
        * Apps que usan Arquitectura de SPA (Single Page Application)
            1. Gmail
            2. Trello
            3. Spotify
        * Apps que usan Arquitectura de Progresive Web Apps (PWA)
            1. Aliexpress
            2. Alibaba
            3. The Guardian
            4. The Washington Post
        * Apps que usan Arquitectura Cliente/Servidor
            1. Facebook
            2. Amazon
            3. WordPress.
    
    3. Bibliografía.

---

### Investigación de los modelos cliente/servidor más comunes

#### Algunos de los modelos de arquitectura web más comunes

1. **Arquitectura de SPA (Single Page Application):** Las Single Page Applications (SPA) revolucionan la experiencia del usuario al cargar todo lo necesario en una única página y actualizarla dinámicamente a medida que interactúa. Esto se logra a través de llamadas AJAX al servidor, lo que evita la necesidad de recargar la página por completo. En una SPA, el servidor actúa principalmente como un Service Layer y no tiene un papel central como en las aplicaciones web tradicionales.

    Las SPA se basan en características como Chunking (construcción de la página en partes), Controllers (separación de vistas y modelos), Templating (binding de datos en templates HTML), Routing (navegación sin recarga de página) y Real-Time Communication (comunicación bidireccional). También hacen uso del almacenamiento local para permitir el funcionamiento sin conexión.

    Ventajas de las SPA incluyen una interfaz de usuario más rápida, mayor interactividad y la capacidad de trabajar sin conexión. Sin embargo, construirlas puede ser más complejo y requiere sólidos conocimientos de JavaScript. También puede ser desafiante elegir las librerías de JavaScript adecuadas para el desarrollo.

    Dadas las ventajas de las SPA, están ganando popularidad rápidamente y plantean la pregunta de si podrían desplazar a las aplicaciones móviles nativas en el futuro.

2. **Arquitectura de Progresive Web Apps (PWA):** Las Progressive Web Apps (PWA) son un estándar web que brinda una experiencia rápida y confiable tanto en dispositivos móviles como de escritorio. Muestran funcionalidades de aplicaciones nativas y tienen características adicionales. Sus principales características incluyen una interfaz similar a una aplicación, capacidad de respuesta completa y compatibilidad con diferentes navegadores.

    Las PWA se pueden instalar fácilmente e incluir a la pantalla de inicio, eludiendo la necesidad de descargar e instalar desde tiendas de aplicaciones. Además pueden ejecutarse sin conexión gracias a la tecnología Service Workers. Se actualizan automáticamente y pueden mandar notificaciones en tiempo real.

    Al implementar PWA, las empresas pueden incrementar el tráfico orgánico de búsqueda, mejorar la visibilidad de la marca y alcanzar una mayor participación de los clientes. Además, presentan una alternativa más asequible a las apps nativas. Su adopción puede llevar a beneficios significativos y una mayor tasa de conversión móvil.

3. **Cliente/Servidor:** La arquitectura Cliente-Servidor consta de dos componentes: el servidor (proveedor de servicios o recursos) y el cliente (consumidor de estos servicios). Los clientes se conectan al servidor para obtener los recursos necesarios. El cliente representa datos y desencadena acciones, mientras tanto, el servidor realiza la mayor parte del trabajo.

    Esta arquitectura requiere que el servidor exponga un mecanismo de comunicación, comúnmente TCP/IP, para admitir la interacción continua y bidireccional entre el cliente y el servidor.

    El cliente y el servidor son aplicaciones independientes, desarrolladas por separado, pero siguen el mismo protocolo de comunicación. La separación permite centralizar la información y las responsabilidades, preservando los datos y facilitando el manejo de múltiples clientes.

    Aunque el cliente y el servidor pueden llevarse a cabo con tecnologías diferentes, es común que el mismo equipo trabaje en ambos. Esto da lugar a tres artefactos: el Cliente, el Servidor y una librería que contiene objetos compartidos.

    * Ventajas:

        * Centralización de la información.
        * Mayor seguridad con protección del servidor.
        * Fácil instalación del cliente.
        * Separación de responsabilidades en la lógica de negocio.
        * Portabilidad con aplicaciones que corren en diferentes plataformas.

    * Desventajas:

        * Gestión de actualizaciones en clientes.
        * Problemas de concurrencia ante múltiples usuarios.
        * Dependen completamente del servidor.
        * Uso de protocolos de bajo nivel.
        * Dificultades en la depuración de errores.

---

### Identificación de ejemplos de aplicaciones que utilizan cada modelo

#### Apps que usan arquitectura de SPA (Single Page Application)

1. **Gmail** Gmail es un destacado ejemplo de una SPA. Al iniciar sesión, se despliega una sola página inicial donde todas las interacciones se llevan a cabo sin recargar la página completa. Las bandejas de entrada, la composición de mensajes, la búsqueda y la visualización de correos se realizan de inmediato, ofreciendo una experiencia sin interrupciones y ágil.

2. **Trello** Trello es una app para organizar proyectos con tableros. Permite a los usuarios elaborar listas, añadir tarjetas y trasladarlas entre distintas fases del proceso. En ella, los usuarios llevan a cabo todas las acciones sin requerir cargar páginas extra. Modificar los tableros y tarjetas es sencillo, y los usuarios pueden contribuir en directo de manera fluida.

3. **Spotify** Spotify emplea una Aplicación de Página Única (SPA) en su versión web. Tras iniciar sesión, se despliega una sola página que habilita a los usuarios a buscar, reproducir y administrar música sin cargar páginas adicionales. Las actualizaciones de la lista de reproducción, la búsqueda de artistas y álbumes, así como la emisión de canciones se llevan a cabo en una misma página, proporcionando una experiencia de usuario sin interrupciones y fluida.

#### Apps que usan arquitectura de Progresive Web Apps (PWA)

Hay una gran variedad de compañías que han implementado esta tecnología en sus webs.
Tenemos varias como pueden ser:
    1. **Aliexpress**: En su caso creció considerablemente tanto el número de usuarios y como las estadísticas que mejoraron con creces.
    2. **Alibaba**
    3. **The Guardian**
    4. **The Washington Post**

#### Apps que usan arquitectura Cliente/Servidor

Muchas apps y servicios modernos usan esta arquitectura para brindar funcionalidades distribuidas y escalables. Ejemplos:

    1. **Facebook** Las redes sociales como Facebook utilizan una arquitectura cliente/servidor para coordinar las interacciones de los usuarios y archivar y restaurar datos.

    2. **Amazon** Los sitios web de comercio electrónico como Amazon utilizan servidores para manejar la base de datos de productos, procesar transacciones y proveer una experiencia de compra en línea.

    3. **WordPress** Plataformas como WordPress usan una arquitectura cliente/servidor para administrar el contenido de los sitios web, guardar datos y contestar a las solicitudes de los visitantes.

---

### Bibliografía

[Arquitectura cliente-servidor](https://reactiveprogramming.io/blog/es/estilos-arquitectonicos/cliente-servidor)
[Progressive Web Apps](https://felixicaza.com/blog/que-son-las-progressive-web-apps)
[Single Page Applications](https://itblogsogeti.com/2014/06/10/single-page-applications-roberto-bermejo-sogeti/)
[Apps que usan arquitectura Single Page Application](https://blog.hubspot.es/website/que-es-single-page-application)
[Apps que usan arquitectura Progresive Web Apps](https://torresburriel.com/weblog/disenando-aplicaciones-web-progresivas-pwa/)
[Apps que usan arquitectura Cliente/Servidor](https://blog.faztweb.com/2017/04/entendiendo-arquitectura-cliente.html)
