This code is based on the instructions from Microservices Deployment Cookbook by Packt. 

Requires Spring Framework STS IDE
Maven

HTTP calls for tests:

curl -H "Content-Type: application/json" -X POST -d'{"timestamp": 1468203975, "userId": "f1196aac-470e-11e6-beb8-9e71128cae77", "latitude": 41.803488, "longitude": -88.144040}' http://localhost:8080/geolocation


curl -H "Content-Type: application/json" -X POST -d '{"timestamp": 1468203975, "userId": "f1196aac-470e-11e6-beb8-9e71128cae77", "latitude": 9.568012, "longitude": 77.962444}' http://localhost:8080/geolocation


curl http://localhost:8080/geolocation
