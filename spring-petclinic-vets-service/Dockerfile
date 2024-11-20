
# Usar la imagen base de OpenJDK para ejecutar aplicaciones Java, esto es una prueba mamamamaadsads
FROM openjdk:17-jdk-slim 

# Mantenedor
LABEL maintainer="tu_email@example.com"
LABEL service="vets-service"

# Directorio de trabajo dentro del contenedor
WORKDIR /app

# Copiar el JAR de la aplicación al contenedor
COPY target/*.jar app.jar

# Comando para ejecutar el JAR
ENTRYPOINT ["java", "-jar", "app.jar"]

