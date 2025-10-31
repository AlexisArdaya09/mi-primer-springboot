# Mi Primer Proyecto Spring Boot

## Información del Proyecto

- **Nombre:** mi-primer-springboot
- **Versión de Spring Boot:** 3.5.7
- **Java:** 17.0.9
- **Build Tool:** Maven

## Estructura del Proyecto

Explica brevemente cada directorio/archivo:

### src/main/java/dev/alefiengo/miprimerspringboot/
- `MiPrimerSpringbootApplication.java`: Este archivo nos ayuda a arrancar mi aplicación Spring Boot, tambien se podria decir que es el punto de entrada.

### src/main/resources/
- `application.properties`: Es donde se agregan configuraciones que utiliza Spring Boot al arrancar.

### src/test/
- En esta carpeta se encuentran los test unitarios e integración, para garantizar la calidad y evitar errores.

### pom.xml
- En este archivo podemos encontrar las dependencias principales de nuestro proyecto, para contrastar seria como un package.json para node.js.

### target/
- En esta carpeta se encuentran los archivos compilados de nuestro proyecto.

## Cómo Ejecutar

\```bash
mvn spring-boot:run
\```

## Dependencias Principales

Lista las dependencias en `pom.xml` y explica brevemente cada una:
- spring-boot-starter-web: Es una dependencia que nos permite arrancar un servidor web y tambien trae los componentes necesarios para desarrollar aplicaciones web RESTful.
- spring-boot-starter-test: Es una dependencia que nos permite ejecutar test unitarios e integración.

## Conceptos Aprendidos

- ¿Qué es Spring Boot?
  - Es un framework de Java que nos facilita crear aplicaciones como: API REST, aplicaciones web, microservicios, etc.
  - Nos facilita la vida a la hora de crear aplicaciones con Java.
- ¿Qué es Maven?
  - Es una herramienta de construccion de proyectos Java.
  - Su función es descargar dependencias de nuestro pom.xml y tambien se encarga compilar y empaquetar la aplicacion.
- ¿Qué significa "Tomcat started on port 8080"?
  - Significa que el servidor web Tomcat ya esta corriendo y escuchando en el puerto 8080.
- ¿Para qué sirve la anotación @SpringBootApplication?
  - Es la anotacion principal de spring boot, que nos permite arrancar nuestro proyecto y agrega procesos necesarios para el arranque de forma automatica.

## Autor
Alexis Rene Ardaya Deromedis - Curso Spring Boot & Kafka