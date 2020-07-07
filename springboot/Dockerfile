FROM openjdk:14
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN ./gradlew build
RUN ./gradlew jar
CMD ["java", "-jar", "./build/libs/demo-0.0.1-SNAPSHOT.jar"]
