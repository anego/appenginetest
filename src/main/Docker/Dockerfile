FROM gcr.io/google_appengine/openjdk8
VOLUME /tmp
ADD appenginetest-1.0-SNAPSHOT.jar app.jar
CMD [ "java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
