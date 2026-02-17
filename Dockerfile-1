FROM amazoncorretto:17
LABEL author="ranganath"
LABEL project="learning"
ADD /target/spring-petclinic-4.0.0-SNAPSHOT.jar /spring-petclinic-4.0.0-SNAPSHOT.jar
EXPOSE 8080/tcp
CMD ["java", "-jar", "spring-petclinic-4.0.0-SNAPSHOT.jar"]
