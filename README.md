# SDAT and Dev OPs QAP 2

- Right-click the pom.xml file and reload project to download dependencies.
- Run: `mvn clean install`
- Run: `docker build -t jivany304/image .`
- Run: `docker push jivany304/image:latest`
- Run: `docker-compose up`
- In postman, make a request to http://localhost:8080/ and at the end type aircraft, airport, city, or passengers.
- You can now use postman to get and set parameters in the database.
