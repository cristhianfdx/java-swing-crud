# CRUD-BASICO-JAVA-MYSQL
CRUD Básico utilizando JForms

Para este ejercicio se requiere hacer un CRUD a una tabla de estudiantes, la solución presentada se realiza utilizando una especie de arquitectura por capas
y una mezcla de MVC, al separar cada proceso en una clase diferente.

Se tienen las siguientes clases:

FrmInterfazGrafica : Contiene la vista, Intefaz Gráfica que permite al usuario interactuar con la información

Controlador: Clase que manipula la logica de negocio, interactua entre la Vista y el modelo permitiendo enviar y recibir datos desde la 
vista y enviarlos al modelo para ser procesados en la base de datos.

ModeloDatos: Clase que manipula los datos y realiza las consultas necesarias a la base de datos.

Conexion: Clase que guarda la configuración necesaria para poder conectarse a la base de datos.

![formulario](https://user-images.githubusercontent.com/40704923/48955326-5a1ff780-ef1b-11e8-8112-f50ed17da700.PNG)




