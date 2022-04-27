# C:\Users\Carlos\Documents\GitHub
 Repositorio para tarea 
1.- Nombre del proyecto: Sistema web para empresa de servicios computacionales
 
2.- Descripción: El proyecto permite automatizar la administración y entrega de los servicios informáticos de la empresa a través de internet a sus clientes. 
Esto contempla sus servicios de mantención, reparación y venta de equipos computacionales como también de proyectos de software. 

3.- Instalación del proyecto: Las carpetas del proyecto que se encuentra en el repositorio de Github se copian a una carpeta local en el equipo, luego se debe
utilizar el editor de código Visual Studio Code. Se requiere tener instalado el lenguaje Python en el equipo, posteriomente estando en la terminal del editor, 
se debe abrir y activar un entorno virtual con la instrucción virtualenv env/Scripts/activate. Se requiere también tener instalado el framework Django, de no 
ser así se debe instalar en la terminal con la instrucción pip install Django. Finalmente, para ejecutar el programa dese debe levantar el servidor en Python
con la instrucción py manage.py runserver. 

4.- Como usar: El sistema cuenta con un menú, en el cual se muestran distintas opciones para ser utilizados por los usuarios del sistema, tales como Usuarios,
Crear Usuarios, Registrarse, Login y salir. El menú de usuarios y de crear usuarios solo puede ser utilizado por los usuarios registrados. Cuando un usuario se
registra y loguea el sistema le da un mensaje de bienvenida. Si el usuario no está registrado, no puede acceder a la página de bienvenida. En la opción usuarios
se muestra un listado de usuarios del sistema; en Crear Usuarios se pueden crear usuarios del sistema a través de un formulario; en Registrarse los clientes y otros
usuarios del sistema de la empresa se pueden registrar; en Login los clientes pueden acceder al sistema, al hacerlo el software les da un mensaje de bienvenida
y en Salir el usuario se sale del sistema con un mensaje de despedida.

5.- Justificación de permisos diferenciados: Las clases Soporte Tecnico y Comercial de la aplicación pertenecen a personal, staff de la empresa, que realizan funciones 
diferentes y que se encuenran en áreas distintas de la empresa. El personal de soporte técnico se ocupa de ejecutar las ordenes de trabajo solicitadas por los clientes;
en cambio el personal comercialse ocupa de la busqueda de clientes, generar una venta o un contrato con un cliente empresa. Por lo cual, el otorgar permisos diferenciados
se justifica para que no interfieran en su ámbito de trabajo. 
