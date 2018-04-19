>A simple skeleton gradle build application using Spring boot at server side and Angular at the client side.

```gradlew bootRun``` - It will first build client resource and move it to server:resources/static. Tomcat server will start in dev mode

```gradlew build```   - It will first build client resource and move it to server:resources/static. Then final jar will jar will be built using spring-boot-gradle-plugin


Angular resources are being instructed to build using gradle-node-plugin (https://github.com/srs/gradle-node-plugin) from gradle. 



 
