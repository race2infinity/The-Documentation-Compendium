Estos son los directorios que estamos utilizando activamente en el desarrollo:

+ [frontend / server / controllers](https://github.com/kylelobo/The-Documentation-Compendium/tree/master/frontend/server/controllers):
Los controladores hacen la lógica empresarial y exponen la API del servidor.
+ [frontend / server / libs](https://github.com/The-Documentation-Compendium/tree/master/frontend/server/libs): Bibliotecas y utilidades.
+ [frontend / server / libs / dao](https://github.com/The-Documentation-Compendium/tree/master/frontend/server/libs/dao): Objetos de Acceso de Datos [DAO] y Objetos de valor [VO]. Clases utilizadas para representar esquemas de bases de datos y facilitar su uso por parte de los controladores.
+ [frontend / templates](https://github.com/The-Documentation-Compendium/tree/master/frontend/templates): plantillas de Smarty utilizado para generar el HTML que se muestra a los usuarios.
+ [frontend / www](https://github.com/The-Documentation-Compendium/tree/master/frontend/www): el contenido completo de la
página de Internet.

### frontend / www

Contenido:

+ js /
+ css /

#### js

Como su nombre lo indica, aquí es donde residen todas las fuentes y marcos de JavaScript. Cuando desee realizar cambios, minimice el javascript y luego cárguelo.

#### css

Similar a js, aquí están los archivos css minificados.

### frontend / servidor

Contenido:

+ dao /
+ controladores /

Ninguno de estos módulos debería ser accesible para el mundo exterior. El único que puede llamarlos es la interfaz de usuario. Por eso están en la carpeta www.

#### DAO / VO

La carpeta *dao* contiene las clases para la capa de acceso a datos. Tiene 2 cosas que saber: *objetos de acceso a datos* y *objetos de valor*. Los *objetos de valor* (VO) no son más que clases que se asignan directamente a cada una de las tablas de la base de datos. Por lo tanto, hay una clase allí llamada Usuarios, ya que hay una tabla con el mismo nombre. Esta clase tiene sus establecedores y captadores para cada uno de los campos de la base de datos. Los *objetos de acceso a datos* (dao) son clases estáticas para cada una de las tablas, y sirven para obtener y hacer persistentes los objetos *vo*.

[Aquí hay más información sobre este modelo](http://www.ibm.com/developerworks/java/library/j-dao/)

#### Controladores

Los controladores son donde se toman las decisiones. El controlador usa los dao's y vo's para tomar decisiones y nunca llama directamente a la base de datos. De esta forma, evitamos tener controladores separados para cada módulo del proyecto.
