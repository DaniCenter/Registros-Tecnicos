## Proyecto de Administración de Fichas Técnicas de Vehículos

Este proyecto de software tiene como objetivo crear una plataforma web para que los administradores puedan registrar y gestionar las fichas técnicas de los vehículos de sus usuarios. La plataforma permitirá a los administradores generar y asignar fichas técnicas de vehículos en formato PDF a los usuarios registrados. Los usuarios podrán acceder a sus fichas técnicas y renovarlas si es necesario.

### Características

El sistema tendrá las siguientes características:

-   Registro de nuevos usuarios con información personal y de vehículo.
-   Generación de fichas técnicas en formato PDF a partir de los datos ingresados.
-   Asignación de fichas técnicas a usuarios registrados.
-   Modificación y eliminación de fichas técnicas.
-   Renovación de fichas técnicas por parte de los usuarios.
-   Administración de usuarios y fichas técnicas por parte de los administradores.

### Herramientas utilizadas

Para la implementación del proyecto se utilizarán las siguientes herramientas:

-   HTML, CSS y JavaScript: se utilizarán para el diseño y la construcción de la interfaz de usuario de la plataforma web.
-   MySQL: un sistema de gestión de bases de datos relacional que se utilizará para almacenar los datos de usuarios y fichas técnicas.

## Instrucciones de Instalación

1.  Clona este repositorio a tu máquina local.
2.  Abre una terminal y navega hasta el directorio raíz del proyecto.
3.  Crea una base de datos MySQL e importa el archivo `database.sql` incluido en el proyecto.
4.  Abre el archivo `config.php` y modifica los valores de las variables `DB_HOST`, `DB_USER`, `DB_PASS` y `DB_NAME` para que coincidan con tu configuración de base de datos MySQL.
5.  Ejecuta la aplicación utilizando la extension "live server" de Visual Studio Code
