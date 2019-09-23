# Prueba Técnica - Programador (Back-end)
La siguiente es una prueba para evaluar a los postulantes a programador **Back-end**.

## INTRODUCCIÓN

Este archivo contiene las especificaciones del caso práctico que se desea desarrollar para evaluar las capacidades técnicas del candidato con relación a las funciones necesarias en el área de Desarrollo de Tracker de Colombia

#### ¿Qué se evaluará?
Principalmente los siguientes aspectos:

1. Programar los módulos Frontend con HTML y Javascript o cualquier Framework de javascript como Angular, Bootstrap o también usando JPA, JSF. Para la parte Backend debe implementar Java JEE usando los conceptos de WAR y EJB y/o RESTFULL. Para la base de datos puede usar Postgres o Mysql.
2. El uso de  patrones de diseño.
3. Orden del código (Buenas prácticas)
4. Creatividad
5. Normalización de base de datos y optimización de almacenamiento
6. Realizar mapeo de entidades de bases de datos por medio de Hibernate (Opcional). 
7. Diagrama entidad-relacion (Entregar el diagrama en cualquier IDE de diseño)

## NOTA
1. Recomendamos emplear un máximo de **4 (días)** y enviar todo lo que puedas.
2. Existen 2 opciones para entregar su proyecto:
    * 1) Deseable si puede entregar el proyecto realizando un commit en la rama master a este repositorio https://github.com/DetektorGit/PruebaTecnica.git en donde primero tendría que clonarlo con su cuenta de GitHub y notificar a la siguiente dirección de correo electrónico  [milena.miranda@detektor.com.co](mailto:milena.miranda@detektor.com.co).
    * 2) Crear un archivo comprimido (_.zip_ o _.rar_) de su proyecto y enviar a la siguiente dirección de correo electrónico  [milena.miranda@detektor.com.co](mailto:milena.miranda@detektor.com.co).
3. Enviar un video del funcionamiento de los módulos a modo de prueba funcional.

## EJERCICIO

Crear un sistema para Gestión de Contratistas el cuál debe contar con 3 módulos:

1. Módulo de crud de empleados (Creación, edición, consulta y eliminación de empleados) cuyos campos pueden ser Nombre, apellido, identificación, tipo de contrato, fecha de nacimiento, dirección, teléfono, email

2. Módulo de crud de contratistas (Creación, edición, consulta y eliminación de contratistas) cuyos campos pueden ser Nombre, apellido, identificación, fecha de nacimiento, dirección, teléfono, email, empresa. Este módulo debe tener la capacidad de asociar o desasociar por cada contratista n cantidad de empleados (tipo DragDrop) definiendo a esta relación el tiempo en horas a trabajar, el día de inicio de trabajo y el nombre de la obra (No es necesario crud de obras).

3. Un informe tipo tabla cuyo contenido sea el detalle de la relación Contratista-Empleado que contenga las siguientes columnas: Nombre Contratista, nombre empleado, tiempo trabajados en horas, horas que faltan para terminar el contrato, nombre de la obra.




