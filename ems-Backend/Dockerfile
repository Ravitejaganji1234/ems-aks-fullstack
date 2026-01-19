# FROM maven:3.9.6-eclipse-temurin-21-alpine

# WORKDIR /ems

# COPY . .

# RUN mvn clean install -DskipTests


# ENV SPRING_DATASOURCE_URL=jdbc:mysql://host.docker.internal:3306/employeedb?createDatabaseIfNotExist=true\
#     SPRING_DATASOURCE_USERNAME=root \
#     SPRING_DATASOURCE_PASSWORD=Naveen@70
 

# EXPOSE 8080

# RUN mv target/*.jar target/app.jar

# ENTRYPOINT [ "java","-jar","target/app.jar" ]


FROM maven:3.9.6-eclipse-temurin-21-alpine

WORKDIR /app

COPY . .

RUN mvn clean install -DskipTests

EXPOSE 8081

RUN mv target/*.jar target/app.jar

ENTRYPOINT [ "java","-jar","target/app.jar" ]



