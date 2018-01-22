FROM centos
RUN yum install -y java
VOLUME C:\Docker_Kubernetes\Docker_Kubernetes
ADD  samplespringboot-0.0.1-SNAPSHOT.jar myapp.jar
RUN sh -c 'touch myapp.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","myapp.jar"]

