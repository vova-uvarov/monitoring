#docker build -t monitoring:v0.0.1 .
#docker tag monitoring:v0.0.1 uvolodia/pets-projects:monitoring_v0.0.1
#docker push uvolodia/pets-projects:monitoring_v0.0.1
FROM adoptopenjdk/openjdk11:alpine-jre
ADD monitoring.jar monitoring.jar

# Set default timezone
ENV TZ=Europe/Moscow

ENTRYPOINT java -jar monitoring.jar
