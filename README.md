# Microservicios con Quarkus

This project uses Quarkus, the Supersonic Subatomic Java Framework.

If you want to learn more about Quarkus, please visit its website: https://quarkus.io/ .

## Clonar el proyecto

Para clonar este proyecto, debe ejecutar el siguiente comando:

```
git clone https://github.com/sebasporras14/Lab-08AREP.git
```

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



### Ejecutar el proyecto en AWS

instalamos Java, git y maven en nuestras instancias EC2

	 sudo yum install java-17-amazon-corretto.x86_64

  ```
  sudo yum install git -y
  ```
  ```
  sudo yum install maven -y
  ```

Se accede al repositorio que acabamos de clonar

	 cd Lab-08AREP

Hacemos la construcción del proyecto

	 mvn clean package install


## Video de la aplicación en funcionamiento

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