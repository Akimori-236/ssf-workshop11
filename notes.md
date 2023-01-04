1. Compile maven project

   `mvn compile`
2. Package maven project

`mvn package`

3. Clean up the maven project

`mvn clean`

4. Run Spring boot locally

`mvn spring-boot:run`

5. Login to railway

`railway login`

6. Init your project to enable railway

 `railway init`

7. Change JDK version under pom.xml

```
	<properties>
		<java.version>11</java.version>
	</properties>
```

8. Push code up to railway

`railway up`

## getting args from cmd line

##### Spring Boot port config

`mvn spring-boot:run -Dspring-boot.run.arguments=--port=8084`

Setting env port value

`set APP_PORT=9090`

###### Resetting env port value

`set APP_PORT=`
