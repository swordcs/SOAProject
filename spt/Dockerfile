FROM centos
COPY spt-0.0.1-SNAPSHOT.jar /usr/local/spt-0.0.1-SNAPSHOT.jar
RUN yum -y install java
EXPOSE 8080
CMD java -jar /usr/local/spt-0.0.1-SNAPSHOT.jar
