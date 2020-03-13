# Docker Mariadb Adminer

Para ejecutar solo hay que correr el siguiente comando:

`docker-compose up -d`

Este comando genera los contenedores requeridos:

* Mariadb
* Adminer

## Acceder al administrador Adminer
Para acceder al servidor por medio del navegador solo se requiere entrar con:

[http://localhost:8080/](http://localhost)

### Datos de acceso:

Los datos de acceso son: 
- Motor de base de datos: **MySQL**
- Servidor: **db**
- Usuario: **test**
- Contraseña: **test**
- Base de datos: **test**

<p align="center"><img src="./readme/1.png" width="800"></p>

Imagen cuando ya se acced:

<p align="center"><img src="./readme/2.png" width="800"></p>

***NOTA: Es posible que tarde en entra ya que primero debe estar el contenedor de mariadb.***

## Acceder con cliente de base de datos:

En este caso vamos a probar con **SequelPro**:

Los datos de acceso son:
* Host: **127.0.0.1**
* Usuario: **test**
* Contraseña: **test**
* Base de datos: **test**
* Puerto: **3306**

<p align="center"><img src="./readme/3.png" width="800"></p>


<p align="center"><img src="https://camo.githubusercontent.com/df0511358c10d85475a8211530a2aea1d0abd5ed/68747470733a2f2f6f63746f6465782e6769746875622e636f6d2f696d616765732f66696c6d746f636174732e706e67" width="600"></p>