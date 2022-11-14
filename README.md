# Hotel-JavaFX


·Descargar e isntalar Git, IntellijIDEA, XAMPP

·Después de instalar Git, ejecutar en la carpeta deseada:

```
$ git clone https://github.com/alexbaikal/Hotel-JavaFX.git
```
·Iniciar base de datos XAMPP y abrir https://localhost/phpmyadmin

·Crear base de datos nueva llamada hotel, importar el archivo hotel.sql ubicado dentro de \Hotel-JavaFX\src\main\java\backend\hotel.sql a la base de datos hotel

·Abrir IntelliJ y abrir el proyecto (File > Open > Hotel-JavaFX)

·Crear una nueva configuración para iniciar el proyecto (_Edit Configurations…_)

·Dar clic a _Add new run configuration…_ y seleccionar Application

·Especificar el Main class, aplicar y Ok

·Especificar parámetros de base de datos dentro de DBConnection.java

·Dar clic derecho a cada uno de los módulos y apretar _Add as a Library…_ dentro de la carpeta lib

·Pulsar Run o Shift+F10


·Usuarios y contraseñas predeterminadas:

	Recepcionista:

		usuario: 1

		contraseña: 1

	Administrador:

		usuario: admin
		
		contraseña: admin
