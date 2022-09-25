# Intrsucciones para la creacion de la Base de datos correspondiente a este ejercicio

1. Instalar MySQL Server
    - `sudo apt-get install mysql-server`
2. Entrar a MySQL
    - `sudo mysql`
3. Crear una Base de datos
    - `create database codigoIoT;`
4. Seleccionar la base de datos
    - `use codigoIoT;`
5. Crear una nueva tabla que contenga los campos deseados
    - ID, fecha, nombre, temperatura, humedad
    - `create table clima (id INT(6) UNSIGNED AUTO_INCREMENT PRIMARY KEY, fecha TIMESTAMP DEFAULT CURRENT_TIMESTAMP, nombre CHAR(248) NOT NULL, temperatura FLOAT(4,2) NOT NULL, humedad INT(3) NOT NULL);`

## Notas 
- Se pueden consultar las bases de datos con el comando `show databases;`
- Puedes consultar las tablas de una BD con el comando `show tables;`
- Puedes consultar los campos de la tabla con el comando `describe clima;`