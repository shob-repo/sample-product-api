sample-product-api
==
Steps to run the app
=

1. Clone the application

 - git@github.com:shob-repo/sample-product-api.git **(using ssh)**
 - https://github.com/shob-repo/sample-product-api.git **(using https)**

2. Build and run the app using maven
	- mvn package
    - java -jar target/spring-boot-rest-product-api-0.0.1-SNAPSHOT.jar
 - Alternatively, you can run the app without packaging,
	- mvn spring-boot:run
The app will start running at http://localhost:8080.
#To access H2 database
- Go to http://localhost:8080/h2
- Open src/main/resources/application.properties and then find username & password (sa & )
- Once logged in you can look at the table name called 'products' with data
3. To Explore API (GET method)
- http://localhost:8080/api/getproductdetails
