FROM openjdk

VOLUME C:\Maven_Fabric8_Plugin\spring-boot-docker-maven-release
ADD maven/spring-boot-docker-0.0.3-SNAPSHOT.jar myapp.jar
RUN sh -c 'touch /myapp.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/myapp.jar"]
