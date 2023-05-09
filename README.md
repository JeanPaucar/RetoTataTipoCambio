# Reto BackEnd

Plantilla de desarrollo con Spring Boot.



### Definición de propiedades

**- application.properties**

***Configuración H2***

- spring.h2.console.enabled=true => Configuración para habilitar consola h2
- spring.datasource.url=jdbc:h2:mem:reto => Configuración de base de datos
- spring.datasource.username=sa => Configuración de usuario
- spring.datasource.password=admin123 => Configuración de contraseña



## Comandos de Ejecución

**- Para generar .jar**

    mvn clean install

**- Para generar imagen docker**

    docker build -t retoback .

**- Para ejecutar docker**

    docker run -p 8080:8080 retoback:latest -d

## Rutas al ejecutar

**- Para Swagger**

[Link Swagger](http://localhost:8080/swagger-ui/index.html)

**- Para repositorio**

[Link GitHub](https://github.com/JeanPaucar/RetoTataTipoCambio)


© 2023 Jean Paucar. All rights reserved
