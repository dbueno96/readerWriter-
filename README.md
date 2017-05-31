# readerWriter
Repositorio los archivos solicitados para la práctica de semáforos. 


Para los dos primeros puntos se debe modifciar el parámetro que recibe la función readerorwriter, de modo que se ajuste a lo solicitado. 
Al usar un valor de 0.1 como parámetro, se consigue que la mayoría de personas sean escritores, y con un valor de 0.9 se consigue que la mayoría de persona sean lectores. Esto ocurre debido a un condicional al interiro de la función. 

Para lograr la correcta sincronización entre lectores y escritores, se deben utilizar dos semáforos y usarlos como se muestra en el pseudocódigo brindado (https://docs.google.com/document/d/1Dup4jR7bvu6p6Zsv4Jqj7uIq63M3T1hTaGmhYE7tm0Q/edit). 
Para esto los semáforos deben iniciarcon un valor de 1, y modificar sus valores según se muestra en el pseudocódigo. 
