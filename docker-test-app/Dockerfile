FROM eclipse-temurin:17
RUN mkdir /opt/app
COPY build/libs/docker-test-app-0.0.1-SNAPSHOT.jar /opt/app/nicdkim_app.jar
CMD ["java", "-jar", "/opt/app/nicdkim_app.jar"]
EXPOSE 8080
