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

1. **Arquitectura de SPA (Single Page Application):** Las Single Page Applications (SPA) actualizan una única página dinámicamente sin recargar por completo, utilizando llamadas al servidor. Este actúa principalmente como una capa de servicio, no central como en aplicaciones web tradicionales.

    * Las Single Page Applications (SPA) se basan en características como Chunking, Controllers, Templating, Routing y Real-Time Communication. También utilizan almacenamiento local para funcionar sin conexión.

    * Ofrecen ventajas como una interfaz más rápida y mayor interactividad, pero su desarrollo puede ser complejo y requiere sólidos conocimientos de JavaScript. Su popularidad está en aumento y plantean la posibilidad de desplazar a las aplicaciones móviles nativas en el futuro.

2. **Arquitectura de Progresive Web Apps (PWA):** Las Progressive Web Apps (PWA) ofrecen una experiencia rápida y confiable, imitando aplicaciones nativas. Se instalan fácilmente en la pantalla de inicio y funcionan sin conexión. Se actualizan automáticamente y envían notificaciones en tiempo real.

    * Su implementación puede aumentar el tráfico de búsqueda, mejorar la visibilidad de la marca y fomentar una mayor participación de los clientes. Además, son una alternativa más asequible a las apps nativas, lo que puede llevar a beneficios significativos y una mayor tasa de conversión móvil.

3. **Cliente/Servidor:** La arquitectura Cliente-Servidor tiene dos componentes: el servidor (proveedor de recursos) y el cliente (consumidor de servicios). Los clientes se conectan al servidor para obtener recursos. El cliente representa datos y desencadena acciones, mientras que el servidor hace la mayor parte del trabajo. Se utiliza TCP/IP para la comunicación. Aunque pueden desarrollarse con tecnologías diferentes, siguen el mismo protocolo, permitiendo la centralización de información y responsabilidades para manejar múltiples clientes.

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

1. **Gmail** Gmail es un ejemplo de Single Page Application (SPA). Todas las interacciones ocurren en una sola página sin recargarla, proporcionando una experiencia ágil y sin interrupciones.

2. **Trello** Trello es una app para organizar proyectos en tableros. Permite crear listas y mover tarjetas entre fases sin cargar páginas adicionales. La modificación es sencilla y se puede colaborar en tiempo real.

3. **Spotify** En la versión web de Spotify, se emplea una Aplicación de Página Única (SPA). Permite buscar, reproducir y gestionar música sin cargar páginas adicionales. Todas las acciones se realizan en una sola página, proporcionando una experiencia fluida y sin interrupciones.

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

[Arquitectura cliente-servidor (autor: Oscar Blancarte)](https://reactiveprogramming.io/blog/es/estilos-arquitectonicos/cliente-servidor)
[Progressive Web Apps (autor: Felix Icaza)](https://felixicaza.com/blog/que-son-las-progressive-web-apps)
[Single Page Applications (autor: Roberto Bermejo)](https://itblogsogeti.com/2014/06/10/single-page-applications-roberto-bermejo-sogeti/)
[Apps que usan arquitectura Single Page Application (autor: Martín Durán)](https://blog.hubspot.es/website/que-es-single-page-application)
[Apps que usan arquitectura Progresive Web Apps (autor: Daniel Torres Burriel)](https://torresburriel.com/weblog/disenando-aplicaciones-web-progresivas-pwa/)
[Apps que usan arquitectura Cliente/Servidor (autor: Fazt Blog)](https://blog.faztweb.com/2017/04/entendiendo-arquitectura-cliente.html)
