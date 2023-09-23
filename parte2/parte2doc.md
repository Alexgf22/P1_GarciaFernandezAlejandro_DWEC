# Parte 2 - Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web

## Indice

    1. Estudio de cómo se ejecuta el código JavaScript en un navegador.

    2. Evaluación de las diferencias de compatibilidad entre navegadores.

    3. Resolución de problemas de compatibilidad en una aplicación web.
        * Validar el código de la página
        * Restablecer estilos CSS
        * Utilizar técnicas válidas
        * Usa Google Chrome
        * Verificar web en diferentes buscadores
            1. Browsershots
            2. IETester
            3. Browser Sandbox

    4. Bibliografía.

---

### Estudio de cómo se ejecuta el código JavaScript en un navegador

JavaScript es un lenguaje interpretado que se ejecuta al cargar una página web en el navegador. Puede estar ubicado en cualquier parte del código HTML y se procesa en el orden en que aparece. Es importante tener en cuenta que los errores en funciones pueden no ser evidentes hasta que se utilizan. Esto significa que la detección de fallos puede no ocurrir inmediatamente.

### Evaluación de las diferencias de compatibilidad entre navegadores

* Es crucial que un sitio web funcione bien en todos los navegadores populares (Firefox, Chrome, Explorer, Opera, etc.) para ofrecer una experiencia uniforme a la mayoría de los usuarios.

* Pueden interpretar el código de manera distinta. Esto garantiza la accesibilidad y destaca la importancia de considerar no solo el público y el diseño al crear un sitio web.

### Resolución de problemas de compatibilidad en una aplicación web

* **Validar el código de la página** Validar el código de un sitio web según estándares del W3C es crucial para asegurar compatibilidad y facilitar futuras actualizaciones. Esto implica identificar y corregir errores, evitando el proceso manual propenso a equivocaciones. Además, contribuye a la simplicidad en el mantenimiento y proyecta profesionalismo.

* **Restablecer estilos CSS** Si no se utiliza CSS, los elementos de la página tienen estilos por defecto que pueden variar entre buscadores y causar dificultades. Restablecer el CSS al principio de la hoja de estilos es una forma útil de volver a empezar y vigilar el aspecto de cada elemento.

* **Utilizar técnicas válidas** Evita atributos de CSS problemáticos en exploradores  populares como IE y Firefox. Buenas prácticas en CSS reducen conflictos.

* **Usa Google Chrome** Usar Google Chrome promueve un código más limpio y estándar, compatible con otros navegadores. Al usar Internet Explorer puede exigir ajustes adicionales para la compatibilidad.

* **Verificar web en diferentes buscadores** Herramientas para comprobar la compatibilidad en los buscadores:

    1. Browsershots:
        * Emula navegadores menos conocidos.
        * Contiene Linux, Windows y BSD.
        * Puede llegar a relentizarse con muchos exploradores.

    2. IETester:
        * Visualiza y emplea motores de JavaScript de varias versiones de Internet Explorer.
        * Funciona solo en Windows y precisa IE7 o superior.

    3. Browser Sandbox:
        * Emula Firefox, Chrome, Opera y Safari.
        * Solo disponible para Windows.
        * No es usable con Internet Explorer.

### Bibliografía

[Ejecución de JavaScript en página web (autor: edgardandrea) 3 agosto 2010 copyright](https://www.edgardandrea.com/como-se-ejecuta-javascript-dentro-de-un-pagina-web/)
[Compatibilidad web entre navegadores (autor: Verónica Milán) 3 junio, 2018 copyright](https://www.lawebera.es/xhtml-css/compatibilidad-web-navegadores.php)
