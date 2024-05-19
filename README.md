# HugoVillacis_Web-API-

DIRECTORIO Y ESTRUCTURA DEL PROYECTO:

El directorio src/main/java alberga las clases Java del proyecto, organizadas en paquetes representados por subdirectorios. Por ejemplo, las clases del paquete com.tuuniversidad.apirest.libro están en com/tuuniversidad/apirest/libro. El directorio src/test/java contiene las clases de prueba, estructuradas de manera similar a las clases Java. El directorio resources incluye recursos estáticos como archivos de configuración, imágenes y archivos HTML. Por último, el directorio target guarda los archivos compilados del proyecto.
![image](https://github.com/HuGoVR13/HugoVillacis_Web-API-/assets/99736512/f3698bbc-99ed-4972-8a3e-45628ae14a60)



El LibroController se encarga de gestionar las solicitudes HTTP y de invocar los servicios pertinentes. Los repositorios LibroRepository y LibroRepositoryImpl establecen métodos para acceder a bases de datos simuladas de libros y ofrecen implementaciones con datos pregrabados para pruebas.

![image](https://github.com/HuGoVR13/HugoVillacis_Web-API-/assets/99736512/778441b1-0518-475a-b615-c2383a2237fa)
![image](https://github.com/HuGoVR13/HugoVillacis_Web-API-/assets/99736512/215f5fa9-b8eb-4170-84c7-90318c5b4e79)
![image](https://github.com/HuGoVR13/HugoVillacis_Web-API-/assets/99736512/142da9cf-6550-4293-8181-584c2fcfa50a)



Para obtener todos los libros, se utiliza el punto final GET /books, que devuelve una lista de todos los libros en la base de datos simulada.
Para obtener un libro por su ID, se accede a través del punto final GET /books/{book_id}, donde {book_id} es el identificador del libro, y devuelve la información correspondiente a ese libro.
Para crear un nuevo libro, se usa el punto final POST /books, permitiendo agregar libros a la base de datos simulada.




PRUEBA EN POSTMAN:


![image](https://github.com/HuGoVR13/HugoVillacis_Web-API-/assets/99736512/dd779dbe-6208-40c7-8b57-4b22b8a19736)




COMO SE EJECUTA:

Puerto 8081



![image](https://github.com/HuGoVR13/HugoVillacis_Web-API-/assets/99736512/3d9e41b4-c646-4b28-9a89-1f126b152cdc)
![image](https://github.com/HuGoVR13/HugoVillacis_Web-API-/assets/99736512/61431c31-d506-4701-8f5c-953939e9acde)

