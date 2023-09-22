# Parte 2 - Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web

## Indice

    1. Estudio de cómo se ejecuta el código JavaScript en un navegador.

    2. Evaluación de las diferencias de compatibilidad entre navegadores.

    3. Resolución de problemas de compatibilidad en una aplicación web.

    4. Bibliografía.

---

### Estudio de cómo se ejecuta el código JavaScript en un navegador

JavaScript, como lenguaje interpretado, implica que el código fuente se convierte en código ejecutable instantáneamente durante su proceso. El intérprete, incorporado en el navegador, se encarga de esta transformación cuando ejecuta la página en el almacenamiento del dispositivo. El código JavaScript puede localizarse en cualquier sección del documento HTML, incluso puede haber múltiples bloques. El orden de análisis sigue la disposición física en el documento, y el código en funciones o coordinadores de eventos solo se interpreta al ser llamado. Esto significa que los errores en funciones pueden permanecer camuflados hasta su invocación.

### Evaluación de las diferencias de compatibilidad entre navegadores

* Un sitio web compatible con todos los navegadores se ve igual en cada uno. Es esencial que funcione correctamente en los buscadores principales como Firefox, Chrome Explorer, Opera...etc .Ya que esto garantiza una buena experiencia para la mayoría de los usuarios.

* Es crucial que una página web funcione de forma adecuada en diversos navegadores, ya que estos traducen el código de manera diferente, lo que puede afectar la visualización. Esto garantiza que la página sea accesible para la mayor cantidad de usuarios. No solamente considerar el público y el diseño al crear una web.

### Resolución de problemas de compatibilidad en una aplicación web

* **Validar el código de la página** Para una mayor compatibilidad con los buscadores es recomendable comprobar el código del sitio web según los estándares del W3C para asegurar compatibilidad entre navegadores y próximas comprobaciones de HTML y CSS. Esto quiere decir analizar tu web para verificar si hay fallos, saber el motivo de cada error y arreglarlos. Validar manualmente es propenso a errores y menos eficiente. Además es importante verificar el código para mayor simplicidad de mantenimiento, para aparentar mayor profesionalidad...

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

[Ejecución de JavaScript en página web](https://www.edgardandrea.com/como-se-ejecuta-javascript-dentro-de-un-pagina-web/)
[Compatibilidad web entre navegadores](https://www.lawebera.es/xhtml-css/compatibilidad-web-navegadores.php)