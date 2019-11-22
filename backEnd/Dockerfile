FROM openjdk:11
WORKDIR usr/src
ENV mysql.host=localhost
ENV mysql.port=3306
ENV mysql.database=USERCREDS
ADD ./target/demo-0.0.1-SNAPSHOT.jar /usr/src/demo-0.0.1-SNAPSHOT.jar
EXPOSE 3306
ENTRYPOINT ["java", "-jar", "/usr/src/demo-0.0.1-SNAPSHOT.jar"]