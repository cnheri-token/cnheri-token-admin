FROM openjdk:8-jre
RUN mkdir /app
COPY cnheri-token-admin-1.0.0-SNAPSHOT.jar /app/
CMD java -jar /app/cnheri-token-admin-1.0.0-SNAPSHOT.jar --spring.profiles.active=prod
EXPOSE 8084