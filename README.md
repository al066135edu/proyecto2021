##CURSO SYMFONY FUE

**Creación de imágenes de docker:**
```
docker-compose -f ./docker/docker-compose.yaml build
```

**Inicio contenedores de docker:**
```
docker-compose -f ./docker/docker-compose.yaml up
```

Dentro del directorio dpcker/mariadb/migrations hay un dump de base de datos básico. 
Este dump se ejecutará la primera vez que se construya en contenedor, generará la base de datos del proyecto y la de mariaDb con los usuarios y contraseñas correspondientes.

**Acceso a la web desde un navegador:**

http://localhost

**Acceso a phpmyadmin (panel para gestionar la base de datos):**

http://localhost:8080

Usuario/Clave: root/root

**Acceso a e-mails enviados en modo local:**

http://localhost:8025

___

Urls disponibles básicas:

- http://localhost
- http://localhost/hello-world
- http://localhost/phpinfo.php
