# argentina_programa_2.0_tpfinal

#Trabajo práctico grupal Introducción a Java

##Se tiene un archivo de texto CSV (cada valor se encuentra separado por una coma) llamado aprobaciones.txt con el siguiente formato:
legajo,nombre y apellido,materia aprobada
Ejemplo:
123,Juan Perez,Frontend
118,Rosa Garcia,Java
123,Juan Perez,Java
115,Nayla Martinez,Python


Se pide:
• Leer el archivo aprobaciones y armar un diccionario (HashMap) con clave legajo
(entero) y dato Estudiante.
• Para la clase Estudiante, tener en cuenta que los atributos son:

o legajo (entero)
o nombreApellido (String)
o materiasAprobadas (ArrayList de String)

• Ofrecer un menú en donde se pueda elegir un número de legajo e indique los
datos del estudiante: nombre y listado de materias aprobadas.

Con el ejemplo anterior, si se eligiera legajo 123, debería mostrar
123 – Juan Perez – Frontend, Java

Nota: tener en cuenta que, si un estudiante no se encuentra en el diccionario, hay que
agregarlo con la materia aprobada, pero, si ya está en el diccionario, solo hay que añadir
una materia en la lista de materias que aprobó.
