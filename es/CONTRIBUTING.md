# Guía de contribución

- Contribuir al Compendio de documentación es bastante fácil. Este documento le muestra cómo empezar

## General

- La [Estructura de la base de código] (./ CODEBASE_STRUCTURE.md) tiene información detallada sobre cómo se estructuran los distintos archivos de este proyecto.
- Asegúrese de que los cambios que realice se ajusten a las [guiás de codificación] (./ CODING_GUIDELINES.md) de este repositorio.

## Envío de cambios

- Bifurcar el repositorio
  - <https://github.com/kylelobo/The-Documentation-Compendium/fork>
- Crea una nueva rama basada en el nombre de lo que pretendes hacer:
  - Ejemplo:

    ````console
    $ git checkout -b NOMBRE_RAMA
    ````

    Si recibe un error, es posible que primero deba buscar fooBar usando

    ````console
    $ git actualización remota && git fetch
    ````

  - Use una rama por reparación/característica
  
- Confirma tus cambios
  - Proporcione un mensaje de git que explique lo que ha hecho.
  - Asegúrate de que tus confirmaciones sigan las [convenciones](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53#file-commit-message-guidelines-md)
  - Envia commit con el repositorio bifurcado
  - Ejemplo:

    ````console
    $ git commit -am 'Agregar algo de fooBar'
    ````

- Empujar a la rama
  - Ejemplo:

    ````console
    $ git push origin BRANCH_NAME
    ````

- Hacer un Pull Request
  - Asegúrese de enviar el PR a la rama <code> fooBar </code>
  - ¡Travis CI te está mirando!

Si sigue estas instrucciones, su PR aterrizará de forma bastante segura en el repositorio principal.