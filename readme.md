Sample spring boot app, output war

Sample rest endpoint http://localhost:8080/v1/hello

Swagger endpoint: http://localhost:8080/swagger-ui/

generate bootable war 
./gradlew bootWar

Run war 
java -jar build/libs/warapp-0.0.1-SNAPSHOT.war
