# Microservicios con Quarkus

This project uses Quarkus, the Supersonic Subatomic Java Framework.

If you want to learn more about Quarkus, please visit its website: https://quarkus.io/ .

### Prerrequisitos

Para hacer uso de esta aplicación debe tener instalado lo siguiente:
+ Java - Lenguaje de programación orientado a objetos.
+ Quarkus - Ejecución eficiente de aplicaciones Java en contenedores Kubernetes.
+ JWT - Decodificación, verificación y generación de JSON Web Tokens.
+ Maven - Herramienta para automatizar la gestión y construcción de proyectos Java.
+ AWS - Plataforma de computación en la nube.

## Descripción del proyecto

El proyecto es una aplicación web estilo Twitter que permite autenticarse y publicar posts en un único hilo, el proyecto está compuesto por un cliente JS alojado en un bucket de S3 de AWS, tres microservicios, cada uno para las entidades Post, User y Stream(hilo), cada uno de estos microservicios está dentro de un contenedor distinto y a su vez todos estos dentro de una instancia EC2 de AWS.

## Arquitectura de la aplicación

![Imagen de WhatsApp 2023-11-03 a las 17 15 42_c92c3b20](https://github.com/sebasporras14/Lab-08AREP/assets/69282634/f01a758e-cdcb-47dc-86d2-ed58053bf6b0)


## Clonar el proyecto

Para clonar este proyecto, debe ejecutar el siguiente comando:

```
git clone https://github.com/sebasporras14/Lab-08AREP.git
```

### Ejecutar el proyecto

una vez clonado se compila y se ejecuta con los siguentes comandos
  ```
  mvn clean install

  ```
  ```
 mvn quarkus:dev
  ```
una vez corriendo se va a:

```
http://localhost:8080/twitter/login

```

![image](https://github.com/sebasporras14/Lab-08AREP/assets/69282634/2d92fd40-aa94-4789-8438-13cc15e1ac18)

y alingresar un usuario se accede al "twitter"

![image](https://github.com/sebasporras14/Lab-08AREP/assets/69282634/f22c158e-e4ea-4b55-9c92-81d69bc5af19)


## Video de la aplicación en funcionamiento en aws

[Video](https://www.youtube.com/watch?v=_QzDmiMpYFA&ab_channel=sebastianporras)

## Construido con

+ [Maven](https://maven.apache.org/) - Dependency Management
+ [Quarkus](https://es.quarkus.io) - Supersonic Subatomic Java
+ [AWS](https://aws.amazon.com/es/) - Cloud Platform
+ [JWT](https://jwt.io) - JSON Web Tokens
+ [Docker](https://www.docker.com/) - Container Lifecycle Manager


## Autores

Sebastian Porras
Camilo Cantillo

## Fecha
11/01/2023
