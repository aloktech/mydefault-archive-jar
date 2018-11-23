FROM openjdk:8
WORKDIR /
CMD ["mkdir", "lib"]
ADD target/{FILENAME}.jar {FILENAME}.jar
ADD target/lib/*.jar lib/
EXPOSE {PORT_NUMBER}
CMD ["java", "-jar","{FILENAME}.jar"]
