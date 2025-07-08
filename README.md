# S14---APLICACION-LIBROS-SQL
Consultas SQL para generar  una propuesta de valor para un nuevo producto a una aplicación de libros.


## Descripción
Te han dado una base de datos de uno de los servicios de aplicaciones para los amantes de los libros. Contiene datos sobre libros, editoriales, autores y calificaciones de clientes y reseñas de libros. Esta información se utilizará para generar una propuesta de valor para un nuevo producto.

1.  Encuentra el número de libros publicados después del 1 de enero de 2000.
2.  Encuentra el número de reseñas de usuarios y la calificación promedio para cada libro.
3.  Identifica la editorial que ha publicado el mayor número de libros con más de 50 páginas (esto te ayudará a excluir folletos y publicaciones similares de tu análisis).
4.  Identifica al autor que tiene la más alta calificación promedio del libro: mira solo los libros con al menos 50 calificaciones.
5.  Encuentra el número promedio de reseñas de texto entre los usuarios que calificaron más de 50 libros
  
## Herramientas utilizadas
![MySQL](https://img.shields.io/badge/:MySQL-E36B26?style=for-the-badge&logo=mysql&logoColor=white&labelColor=101010)</br>

![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)


## Conclusiones
1. 819 libros publicados después del 1 de enero de 2000.
2.  Se obtuvo la tabla correspondiente, el libro con calificación 5 y mayor número de reseñas (16) fue el de indentificador 17.
3.  Penguin books
4.  J.K. Rowling/Mary GrandPré
5.  Los usuarios que califiacron más de 50 libros diferentes, en promedio escriben 1,394.53 reseñas escritas.
   
## Profundización tecnica
SELECT  COUNT/SUM/AVG(col1) AS new_value
FROM table1
FULL/LEFT/RIGHT/INNER JOIN table2 ON table1.col=table2.col
WHERE col2 > '--' 
GROUP BY table-.col-
HAVING --- >----
ORDER BY value/col DESC/ASC
LIMIT # ;
